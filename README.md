## HTML5 base

Base to kickstart new projects. Using gulp and inspired by BEM structure.

### Files structure

Uses BEM structure. Jade and LESS files are organized by elements with blocks inside.

- dist
	- css
	- img
	- js
	- _home.html_
- src
	- img
	- js
		- _app.js_
		- vendor
			- _jquery.min.js_
	- jade
		- element
			- _element.jade_
			- blocks
				- _block1.jade_
				- _block2.jade_
	- less
		- element
			- _element.less_
			- blocks
				- _block1.less_
				- _block2.less_

### Gulp

Gulp is used to :
- Compile Jade files
- Compile LESS files
- Minify and prefix CSS
- Uglify, minify and concatenate JS
- Optimize images with image-min
- Create a LiveReload Server
- Give JS and HTML hints
- Give files sizes

## How to use

* `npm install` to install the npm packages
* `gulp install` to create the dist/ folder
* `gulp` to launch gulp default task
* `gulp images` to optimize images