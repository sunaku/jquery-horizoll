jquery.horizoll.js
==================

Keyboard and mouse enabled horizontal screen
scrolling plugin, with automatic realignment.

Written in 2013 by Suraj N. Kurapati for
Readably https://github.com/sunaku/readably
and thus distributed under the ISC license.

Requirements
------------

Requires: jQuery 1.2.6 or newer
http://docs.jquery.com/Release:jQuery_1.2.6

Optional: jquery-mousewheel 3.1.5 or newer
https://github.com/brandonaaron/jquery-mousewheel

Usage
-----

Include necessary scripts in HTML:

```html
<script src="jquery-1.2.6.min.js"></script>
<script src="jquery.horizoll.js"></script>
<!-- Optional: --><script src="jquery.mousewheel.js"></script>
```

Force horizontal scrolling in CSS:

```css
html, body {
  height: 96%;
  margin: 1%;
  padding: 0;
}
```

Columnize the body content in CSS:

```css
body {
  column-gap: 0;
  -moz-column-gap: 0;
  -webkit-column-gap: 0;

  column-count: auto;
  -moz-column-count: auto;
  -webkit-column-count: auto;

  /* Optional: */ column-width: 26em;
  /* Optional: */ -moz-column-width: 26em;
  /* Optional: */ -webkit-column-width: 26em;

  /* Optional: */ column-rule: thin dashed whitesmoke;
  /* Optional: */ -moz-column-rule: thin dashed whitesmoke;
  /* Optional: */ -webkit-column-rule: thin dashed whitesmoke;
}
```
