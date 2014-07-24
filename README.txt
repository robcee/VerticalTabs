Vertical Tabs for Firefox 29 and beyond
=======================================

This Firefox add-on arranges tabs in a vertical rather than horizontal
fashion.  It is heavily inspired by and borrows ideas from the excellent
Tree Style Tab add-on.

Download & Install: http://people.mozilla.org/~rcampbell/VerticalTabs.xpi

TODO:

* Currently, Uninstall leaves Tabs in the Sidebar. Should restore without
  requiring an update.

* Resizing to minimum size can cause some issues. Explore hiding tab labels
  below threshold.

Goals:

* Ability to arrange tabs in groups (instead of arbitrary trees) plus
  some group-related features (collapse group, tab previews, etc.)

* Very few other features and hopefully little or no preference settings.
  Instead a good JavaScript API might be provided for other extensions
  (e.g. JetPack SDK based) to provide additional features.

* Native look and feel.

* Readable and maintainable code, taking latest Mozilla practices into
  account.  No eval() hacks.

License: Mozilla Public License Version 1.1
