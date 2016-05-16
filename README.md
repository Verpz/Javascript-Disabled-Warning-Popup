# Javascript-Disabled-Warning-Popup

[Website] (http://verpz.github.io/Javascript-Disabled-Warning-Popup)

Will activate a light-weight popup when a user has disabled Javascript notifying them that some site features will be broken.

Uses Javascript to remove the popup if JS is enabled. If JS is disabled it will show the popup.

Uses a CDN, this is very fast and light weight.

Live Demo: http://codepen.io/Verpz/pen/WweRWJ (It will always be visible for demonstration purposes).

* No jQuery Or 3rd Party Library Required.

Note: If you would like to customize the CSS, download js-warn.css.

To install simply add the following code to the bottom of your body tag:
```
<div>
  <link rel="stylesheet" type="text/css" href="https://cdn.rawgit.com/Verpz/Javascript-Disabled-Warning-Popup/b10b9ebe28a92ffe746eb7e6fb6e0d3497c3afdd/js-warn.css">
  <input type="checkbox" id="js-hide" />
  <div class="js-warn" id="js-warn-exit"><h1>Javascript Is Disabled</h1><p>Javascript seems to be disabled. This will break some site features.</p>
  <p>To enable Javascript click <a href="http://www.enable-javascript.com/" target="_blank">here</a></p><label for="js-hide">Close</label></div>
  <script>var jswarn = document.getElementById("js-warn-exit"); jswarn.parentNode.removeChild(jswarn);</script>
</div>
```
Or The Minified Version (CDN Is Minified As Well)

```
<div> <link rel="stylesheet" type="text/css" href="https://cdn.rawgit.com/Verpz/Javascript-Disabled-Warning-Popup/b10b9ebe28a92ffe746eb7e6fb6e0d3497c3afdd/js-warn-min.css"> <input type="checkbox" id="js-hide"/> <div class="js-warn" id="js-warn-exit"><h1>Javascript Is Disabled</h1><p>Javascript seems to be disabled. This will break some site features.</p><p>To enable Javascript click <a href="http://www.enable-javascript.com/" target="_blank">here</a></p><label for="js-hide">Close</label></div><script>var jswarn=document.getElementById("js-warn-exit"); jswarn.parentNode.removeChild(jswarn);</script> </div>
```

Also, I suggest not running this code on every page of your website, it will show everytime the page is loaded and may annoy users travelling between pages.

![Demo](http://i.imgur.com/Yq8jk7M.png)

