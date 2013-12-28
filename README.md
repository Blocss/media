# Blocss Dimensions – v1.0.0

A [Blocss](https://github.com/Blocss/blocss/) component to place any image- and text-like content side-by-side.

Read more about [Blocss](https://blocss.github.io/blocss).

## Installation

* [Bower](http://bower.io/): `bower install --save blocss-media`
* Download: [zip](https://github.com/Blocss/media/zipball/master)
* Git: `git clone https://github.com/Blocss/media`

## Available classes

* `.media` - The core component class
* `.media__img` - The child class for the image
* `.media__img` - The child modifyer to reverse the image
* `.media__body` - The child class for the text

## Usage

Like many components, media relies on a core component class
that is extended by additional modifier classes. This component works best for
small-scale image-content pairs:

```html
<div class="media">
    <div class="media__img  [media__img--rev]">
        <img src="img.png" alt="">
    </div>
    <div class="media__body">
        Bram Smulders @bramsmulders
        …
    </div>
</div>
```

## Browser support

* Google Chrome (latest)
* Opera (latest)
* Firefox 4+
* Safari 5+
* Internet Explorer 8+