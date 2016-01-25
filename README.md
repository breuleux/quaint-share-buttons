
quaint-share-buttons
====================

This plugin lets you embed share buttons on a page.


## Install

    quaint --setup share-buttons


## Sample use

```quaint
share ::
  facebook
  twitter
  google+
  reddit
  email
```

For styling purposes, know that the generated code will look like
this:

    <div class="share-buttons">
       <a href="https://facebook.com/sharer/..." ...>
         <img src=".../facebook.svg">
       </a>
       ...
    </div>



## Macros

### `share ::`

Specify which buttons you want to display and in what order, one by
line.

The following code will add every button that is currently available:

```quaint
share ::
  facebook
  twitter
  google+
  reddit
  email
```

I grant that's not a lot of options, but more will be added.



## Attribution

The buttons generated by `quaint-share-buttons` are from the 
[Social Flat Rounded Rects](https://www.iconfinder.com/iconsets/social-flat-rounded-rects)
icon set by [Aha-Soft](http://www.aha-soft.com/),
released under the [Creative Commons 3.0](http://creativecommons.org/licenses/by/3.0/)
license (free to use).

