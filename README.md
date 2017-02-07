# Stack Overflow theme 2 for jsonresume 

## Features other than the original json resume stackoverflow theme: ##
* Printable version with custom CSS. <br/>
To make the above work use wkhtmltopdf terminal software. You may need to zoom argument/feature to get a presentable pdf version.
* Added pointer and date to the awards list.

[DEMO](https://themes.jsonresume.org/stackoverflow2)

## Getting started

### Install the command line

Create your resume in json on [jsonresume](https://jsonresume.org)

The official [resume-cli](https://github.com/jsonresume/resume-cli) to run the development server.

Go ahead and install it:

```
sudo npm install -g resume-cli
```
### Install and serve theme

This is a theme for JSON Resume. It is available via npm:

```
npm install jsonresume-theme-stackoverflow2
```

then change directory: 

`cd node_modules/jsonresume-theme-stackoverflow2/`

And simply run:

```
resume serve
```

You should now see this message:

```
Preview: http://localhost:4000
Press ctrl-c to stop
```

NOTE : To see detailed documentation see the original parent theme which is jsonresume-theme-stackoverflow
