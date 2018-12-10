Allert.js
=========

A simple JavaScript notification library

Check out this [demo page](http://philippesilva.com/allert/ "Demo")

## Installation

Download allert.js:
- from [Github](https://raw.githubusercontent.com/philippesilva/allert/master/allert.js)
- with npm: `npm install allert`.

Usage
-----

To call a notification, use `allert(text, options)`. Examples :

    allert('Default');
    allert('Options', { type: 'success', icon: 'fa fa-check' });   // type matches CSS class `.alert.type`
    allert('Yeeaahh!!!', { duration: '2000' } // time is ms

By **Philippe Silva**