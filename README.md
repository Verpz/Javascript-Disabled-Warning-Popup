# Javascript-Disabled-Warning
Will activate a light-weight popup when a user has disabled Javascript notifying them that some site features will be broken.

Uses jQuery to remove the popup if JS is enabled. If JS is disabled it will not hide and then give the user an option to close it.

* Requires jQuery

To install simply add the following code to <head>:
```
<div>
  <link rel="stylesheet" type="text/css" href="https://cdn.rawgit.com/Verpz/Javascript-Disabled-Warning/master/js-warn.css">
  <div class="js-warn" id="js-warn-exit"><h1>Javascript Is Disabled</h1><p>Javascript seems to be disabled. This will break some site features.</p>
  <p>To enable Javascript click <a href="http://www.enable-javascript.com/" target="_blank">here</a></p><div>
  <script>$("div.js-warn").hide()</script>
</div>
```
