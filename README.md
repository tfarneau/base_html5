## HTML5 base

Base to kickstart new projects. Using gulp and inspired by BEM structure.

### Structure

Uses BEM structure. Jade and LESS files are organized by elements with blocks inside.

- dist
	- css
	- img
	- js
	- [...].html
- src
	- img
	-js
		- vendor
	- jade
		- element
			- element.jade
			- blocks
				- block1.jade
				- block2.jade
	- less
		- element
			- element.less
			- blocks
				- block1.less
				- block2.less

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