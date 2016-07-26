# 2016-cherub-notebooks

What's inside cherubs' notebooks

https://medillcherubs.github.io/2016-cherub-notebooks/

Paste this into your Wordpress post, under the "Text" tab instead of the "Visual" tab:

```
[raw]
<div id="github-container"></div>
<script> var pymParent = new pym.Parent("github-container", "//medillcherubs.github.io/2016-cherub-notebooks/index.html", {}); </script>

<!-- Edit: https://github.com/medillcherubs/2016-cherub-notebooks/edit/gh-pages/index.html -->
[/raw]
```

Make sure the following code is at the bottom of your `index.html`:

```
<script src="https://code.jquery.com/jquery-1.11.3.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/pym/0.4.5/pym.min.js"></script>
<script> $(function(){ var pymChild = new pym.Child({polling: 500}); }); </script> 
```
