# react-plugin-tutorial
How to build a react plugin from scratch

initial package.json:
```
{
	"name": "grid-splitter-react",
	"version": "1.0.3",
	"description": "A grid splitter for React, resizable with splitter grid",
	"main": "dist/index.js",
	"scripts": {
	},
	"module": "dist/index.js",
	"repository": {
		"type": "git",
		"url": "git+https://github.com/%22uriegel/grid-splitter-react%22%2C.git"
	},
	"author": "uriegel",
	"license": "MIT",
	"files": [
		"dist"
	],	
	"bugs": {
		"url": "https://github.com/%22uriegel/grid-splitter-react%22%2C/issues"
	},
	"homepage": "https://github.com/%22uriegel/grid-splitter-react%22%2C#readme"
}
``` 

# Creating Sample app
```
mkdir sample
cd sample
npm init
npm install webpack webpack-cli --save-dev
```