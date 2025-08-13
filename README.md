Masonry Gallery
===============

Masonry Gallery is a Views style plugin that displays images in a traditional
masonry grid layout. 

The module arranges images in columns based on their height, filling the
available space as evenly as possible with minimum gaps at the bottom of the 
gallery. At the same time, it tries to preserve left-to-right visual order of 
the images. 

Technically this gallery uses CSS for the basic column layout and JavaScript 
to control the image order.

Features
========

- Responsive masonry grid layout for images.
- Optimised image loading (lazy loading).
- Captions placed either statically below the image or shown on mouse hover over the image bottom.
- Ability to adjust caption style without writing additional CSS.
- Ability to use rich text for captions (by adding text fields in Views).
- Several loader icon styles to choose from.
- Option to display a low resolution preview while the full image is loading.

Installation
------------

- Install this module using the official Backdrop CMS instructions at
  https://backdropcms.org/guide/modules

- Visit the configuration page under Administration > Configuration > Media >
  Masonry Gallery (admin/config/media/masonry_gallery) to configure the global
  settings.

- Enable and configure the Masonry Gallery in a view's format section. This plugin requires
  one image field and may optionally use one text field as a source for captions.


Issues
------

Bugs and Feature requests should be reported in the Issue Queue:
https://github.com/backdrop-contrib/masonry_gallery/issues

Known Issues
------------

Some lightbox modules may display images in a wrong sequence following columns direction instead of intended left to right order.

Current Maintainers
-------------------

- [Pavel](https://github.com/korontari)
- Co-maintainers are welcome.

Credits
-------

- Written for Backdrop by [Pavel](https://github.com/korontari).
- [LazyLoad](https://github.com/verlok/vanilla-lazyload) plugin(MIT license) by [Andrea Verlicchi](https://github.com/verlok).

License
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.

