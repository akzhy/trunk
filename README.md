<p align="center">
  <img src="trunk.png" alt="logo"/>
</p>

# Trunk

![](https://img.shields.io/badge/trunk.css-1.0.0-brightgreen.svg) ![](https://img.shields.io/badge/License-MIT-blue.svg) ![](https://img.shields.io/badge/size-~4kB-9c27b0.svg)

[Webpage](http://akzhy.com/shelf/trunk) | [Demo page](http://trunk.akzhy.com/)

Trunk is a lightweight css framework that aims to achieve responsive grid layout. Trunk follows the same method as that of materialize to achieve this.

## Usage

Download the files and include it as follows
```html
<link href="dist/trunk.min.css" rel="stylesheet" type="text/css"/>
```

Or include from jsdelivr
```html
<link rel="stylesheet" type="text/css" href="https://cdn.jsdelivr.net/gh/akzhy/trunk/dist/trunk.min.css"/>
```

### Grid

Grids are created in the same way as that of Materialize.css

A basic grid can be created as follows

```html
<div class="container">
    <div class="row">
        <div class="col s12 m6 l4 xl3"></div>
    </div>
</div>
```

Equal height columns can be created by adding the class `flex` to `.row`
```html
<div class="container">
    <div class="row flex">
        <div class="col s12 m4"></div>
        <div class="col s12 m4"></div>
        <div class="col s12 m4"></div>
    </div>
</div>
```

### Buttons

Buttons can easily be created with the btn class. There are four different types of buttons, adding the btn class alone will produce the default style, other styles are primary, secondary and danger.

```html
<button class="btn">Default Button</button>
<button class="btn primary">Primary Button</button>
<button class="btn secondary">Secondary Button</button>
<button class="btn danger">Danger Button</button>
```

### Utility Classes

There are a few utility classes, such as

 * `.full-width` - For applying 100% width
 * `.hidden` - For applying display none
 * `.center` - On `.row.flex`, this will center the columns horizontally
