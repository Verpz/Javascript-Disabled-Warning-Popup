# Javascript-Disabled-Warning

http://verpz.github.io/Javascript-Disabled-Warning

Will activate a light-weight popup when a user has disabled Javascript notifying them that some site features will be broken.

Uses jQuery to remove the popup if JS is enabled. If JS is disabled it will show the popup.

Uses a CDN, this is very fast and light weight.

Live Demo: http://codepen.io/Verpz/pen/WweRWJ (It will always be visable for demonstration purposes).

* Requires jQuery

Note: If you would like to customize the CSS, download js-warn.css.

To install simply add the following code to the header:
```
<div>
  <link rel="stylesheet" type="text/css" href="https://cdn.rawgit.com/Verpz/Javascript-Disabled-Warning/e5dd42110117aeed7c78434af0fb96524ef4c102/js-warn.css">
  <input type="checkbox" id="hide" />
  <div class="js-warn" id="js-warn-exit"><h1>Javascript Is Disabled</h1><p>Javascript seems to be disabled. This will break some site features.</p>
  <p>To enable Javascript click <a href="http://www.activatejavascript.org/" target="_blank">here</a></p><div>
  <label for="hide">Close</label>
  <script>$("div.js-warn").hide()</script>
</div>
```
Or The Minified Version (CDN Is Minified As Well)

```
<div> <link rel="stylesheet" type="text/css" href="https://cdn.rawgit.com/Verpz/Javascript-Disabled-Warning/e5dd42110117aeed7c78434af0fb96524ef4c102/js-warn-min.css"> <input type="checkbox" id="hide"/> <div class="js-warn" id="js-warn-exit"><h1>Javascript Is Disabled</h1><p>Javascript seems to be disabled. This will break some site features.</p><p>To enable Javascript click <a href="http://www.activatejavascript.org/" target="_blank">here</a></p><div> <label for="hide">Close</label> <script>$("div.js-warn").hide()</script> </div>
```

![Demo](http://i.imgur.com/Yq8jk7M.png)

Apache License 2.0
