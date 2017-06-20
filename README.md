bootstrap-select-ajax
================

[![Latest release](https://img.shields.io/github/release/silviomoreto/bootstrap-select.svg)](https://github.com/silviomoreto/bootstrap-select/releases/latest)
[![Bower](https://img.shields.io/bower/v/bootstrap-select.svg)]()
[![npm](https://img.shields.io/npm/v/bootstrap-select.svg)](https://www.npmjs.com/package/bootstrap-select)
[![NuGet](https://img.shields.io/nuget/v/bootstrap-select.svg)](https://www.nuget.org/packages/bootstrap-select/)
[![CDNJS](https://img.shields.io/cdnjs/v/bootstrap-select.svg)](https://cdnjs.com/libraries/bootstrap-select)

[![License](https://img.shields.io/badge/license-MIT-brightgreen.svg)](LICENSE)
[![Dependency Status](https://david-dm.org/silviomoreto/bootstrap-select.svg)](https://david-dm.org/silviomoreto/bootstrap-select)
[![devDependency Status](https://david-dm.org/silviomoreto/bootstrap-select/dev-status.svg)](https://david-dm.org/silviomoreto/bootstrap-select#info=devDependencies)

Notice: This package is forked from [silviomoreto/bootstrap-select](https://github.com/silviomoreto/bootstrap-select). I just modify a little code for ajax. 

Bootstrap-select is a jQuery plugin that utilizes Bootstrap's dropdown.js to style and bring additional functionality to standard select elements.

<a href="http://silviomoreto.github.io/bootstrap-select/"><img src="https://cloud.githubusercontent.com/assets/2874325/18023324/42cf556c-6bb5-11e6-84ce-35be08ae57ba.gif" alt="bootstrap-select demo"></a>

## Demo and Documentation

You can view a live demo and some examples of how to use the various options [here](http://silviomoreto.github.io/bootstrap-select).

Bootstrap-select's documentation, included in this repo in the root directory, is built with MkDocs and publicly hosted on GitHub Pages at http://silviomoreto.github.io/bootstrap-select. The documentation may also be run locally.


### Running documentation locally

1. If necessary, [install MkDocs](http://www.mkdocs.org/#installation).
3. From the `/bootstrap-select/docs` directory, run `mkdocs serve` in the command line.
4. Open `http://127.0.0.1:8000/` in your browser, and voilà.

Learn more about using MkDocs by reading its [documentation](http://www.mkdocs.org/).

## Authors

[Silvio Moreto](https://github.com/silviomoreto),
[Ana Carolina](https://github.com/anacarolinats),
[caseyjhol](https://github.com/caseyjhol),
[Matt Bryson](https://github.com/mattbryson), and
[t0xicCode](https://github.com/t0xicCode).

## Usage

Create your `<select>` with the `.selectpicker` class.
```html
<select class="selectpicker">
  <option>Mustard</option>
  <option>Ketchup</option>
  <option>Barbecue</option>
</select>
```

If you use a 1.6.3 or newer, you don't need to do anything else, as the data-api automatically picks up the `<select>`s with the `selectpicker` class.

If you use an older version, you need to add the following either at the bottom of the page (after the last selectpicker), or in a [`$(document).ready()`](http://api.jquery.com/ready/) block.
```js
// To style only <select>s with the selectpicker class
$('.selectpicker').selectpicker();
```
Or
```js
// To style all <select>s
$('select').selectpicker();
```

Checkout the [documentation](http://silviomoreto.github.io/bootstrap-select) for further information.
