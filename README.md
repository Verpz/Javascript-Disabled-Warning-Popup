# Javascript-Disabled-Warning

http://verpz.github.io/Javascript-Disabled-Warning

Will activate a light-weight popup when a user has disabled Javascript notifying them that some site features will be broken.

Uses jQuery to remove the popup if JS is enabled. If JS is disabled it will show the popup.

* Requires jQuery

To install simply add the following code to the header:
```
<div>
  <link rel="stylesheet" type="text/css" href="https://cdn.rawgit.com/Verpz/Javascript-Disabled-Warning/master/js-warn.css">
  <div class="js-warn" id="js-warn-exit"><h1>Javascript Is Disabled</h1><p>Javascript seems to be disabled. This will break some site features.</p>
  <p>To enable Javascript click <a href="http://www.enable-javascript.com/" target="_blank">here</a></p><div>
  <script>$("div.js-warn").hide()</script>
</div>
```
Or The Minified Version

```
<div> <link rel="stylesheet" type="text/css" href="https://cdn.rawgit.com/Verpz/Javascript-Disabled-Warning/master/js-warn.css"> <div class="js-warn" id="js-warn-exit"><h1>Javascript Is Disabled</h1><p>Javascript seems to be disabled. This will break some site features.</p><p>To enable Javascript click <a href="http://www.enable-javascript.com/" target="_blank">here</a></p><div> <script>$("div.js-warn").hide()</script></div>
I plan to add a close button.
```
I plan to add a close button.

![Demo](https://i.imgur.com/2FXbSfL.png)
