# strapdown-topbar
A topbar modification for [strapdown.js](http://strapdownjs.com/) (markdown-based webpages)  
[![cdnjs-ready](https://img.shields.io/badge/cdnjs-ready-brightgreen.svg)](https://cdnjs.com/libraries/strapdown-topbar) [![mobile-ready](https://img.shields.io/badge/mobile-ready-blue.svg)](https://github.com/joedf/strapdown-topbar/releases/latest)
 
## Examples
- Example #1: _Left aligned top links_ [[link]](http://joedf.github.io/strapdown-topbar/template.html)
- Example #2: _Right aligned top links_ [[link]](http://joedf.github.io/strapdown-topbar/template-right.html)
- Example #3: (MFixed) _Fixed topbar on mobile devices_ [[link]](http://joedf.github.io/strapdown-topbar/template-mfixed.html)
- Example #4: _Testing Header anchor v-alignment_ [[link]](http://joedf.github.io/strapdown-topbar/header-test.html)
- Example #5: (MFixed) _Testing Header anchor v-alignment_ [[link]](http://joedf.github.io/strapdown-topbar/header-test-mfixed.html)
  
## Usage
Have your topbar setting in the `<body>`.
```HTML
<topbar style="display:none;">
	<item><a href="#">Home</a></item>
	<item><a href="#">About</a></item>
	<menu name="Dropdown Menu">
		<item><a href="#">Item #1</a></item>
		<item><a href="#">Item #2</a></item>
		<item><a href="#">Item #3</a></item>
		<item></item> <!-- add a divider -->
		<item><a href="#">Item #4</a></item>
	</menu>
	<toc>My TOC</toc>
	<item><small>(Powered by <a href="http://strapdownjs.com/">StrapDown.js</a>)</small></item>
</topbar>
```
Then, simply include `strapdown-topbar.js` **AFTER** `strapdown.js`.
```HTML
<script src="http://strapdownjs.com/v/0.2/strapdown.js"></script>
<!-- Include it AFTER strapdown -->
<script src="assets/strapdown/strapdown-topbar.min.js"></script>

<!-- Example: Manually adding a logo -->
<!-- Include it AFTER EVERYTHING -->
<script src="assets/logo.js"></script>
```
**NOTE!** Want more speed? Now available on [cdnjs](https://cdnjs.com/libraries/strapdown-topbar)
