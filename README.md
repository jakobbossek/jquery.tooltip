jquery.tooltip
==============

Simple jQuery based tooltip plugin for rudimentary tooltips with few options.

Usage
=====

Simply use an arbitrary jQuery selector to select the elements which you want to display tooltips on hover and hook the
plugin to the selection. For example if we want to display tooltips for each link in the document with a title attribute,
we can use the following snipplet to realize this. Keep in mind that the tooltip text is extracted from the ```title``` attribute
of the elements.

```JavaScript
    jQuery(document).ready(function($) {
      $("a[title]").tooltip();
    });
```

There are a few options which can be provided to the plugin. For example setting ```sticky``` to ```true``` results in
sticky tooltips, which will not follow the mouse movement. Take a look at the defaults in the plugin for more options.
