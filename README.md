# Javascript-Disabled-Warning

http://verpz.github.io/Javascript-Disabled-Warning

Will activate a light-weight popup when a user has disabled Javascript notifying them that some site features will be broken.

Uses Javascript to remove the popup if JS is enabled. If JS is disabled it will show the popup.

Uses a CDN, this is very fast and light weight.

Live Demo: http://codepen.io/Verpz/pen/WweRWJ (It will always be visable for demonstration purposes).

* No jQuery Or 3rd Party Library Required.

Note: If you would like to customize the CSS, download js-warn.css.

To install simply add the following code to the header:
```
<div>
  <link rel="stylesheet" type="text/css" href="https://cdn.rawgit.com/Verpz/Javascript-Disabled-Warning/b2b2652971cd25a12df2a7f18d23209ff7cc17dd/js-warn.css">
  <input type="checkbox" id="hide" />
  <div class="js-warn" id="js-warn-exit"><h1>Javascript Is Disabled</h1><p>Javascript seems to be disabled. This will break some site features.</p>
  <p>To enable Javascript click <a href="http://www.enable-javascript.com/" target="_blank">here</a></p><div>
  <label for="hide">Close</label>
  <script>var jswarn = document.getElementById("js-warn-exit"); jswarn.parentNode.removeChild(jswarn);</script>
</div>
```
Or The Minified Version (CDN Is Minified As Well)

```
<div> <link rel="stylesheet" type="text/css" href="https://cdn.rawgit.com/Verpz/Javascript-Disabled-Warning/b2b2652971cd25a12df2a7f18d23209ff7cc17dd/js-warn.css"> <input type="checkbox" id="hide"/> <div class="js-warn" id="js-warn-exit"><h1>Javascript Is Disabled</h1><p>Javascript seems to be disabled. This will break some site features.</p><p>To enable Javascript click <a href="http://www.enable-javascript.com/" target="_blank">here</a></p><div> <label for="hide">Close</label> <script>var jswarn=document.getElementById("js-warn-exit"); jswarn.parentNode.removeChild(jswarn);</script> </div>
```

![Demo](http://i.imgur.com/Yq8jk7M.png)

Apache License 2.0
