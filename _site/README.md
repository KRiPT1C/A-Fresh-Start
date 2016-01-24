# A-Fresh-Start
This site is basically a blank canvas for quickly building a Jekyll site.
This is a pretty bias setup. Feel free to do with it whatever you like.I would personally start by deleting the helloworld.html file and removing the include from the index.html.
This Jekyll setup is powered by Gulp for Sass, autoprefixer, and browsersync
A lot of credit goes to Shaky Shane and Travis Neilson. Shane mostly for the original gulpfile and Travis for the great videos that helped me make sense of it. (also the file structure in the assets directory)
If you have found this repository it is likely due to the work that one or both of them have done. This is my 1st foray into the world of Jekyll, gulp, and sass and most of what it takes to get this site working. My development knowledge is limited but growing. If you have questions I will do my best to help but you likely already know more than I do.

## System Preparation

To use this starter project, you'll need the following things installed on your machine.

1. [Jekyll](http://jekyllrb.com/) - `$ gem install jekyll`
2. [NodeJS](http://nodejs.org) - use the installer.
3. [GulpJS](https://github.com/gulpjs/gulp) - `$ npm install -g gulp` (mac users may need sudo)

## Local Installation

1. Clone this repo, or download it into a directory of your choice.
2. Inside the directory, run `npm install`.

## Usage

**development mode**

This will give you file watching, browser synchronisation, auto-rebuild, CSS injecting etc etc.

```shell
$ gulp
```

**jekyll**

As this is just a Jekyll project, you can use any of the commands listed in their [docs](http://jekyllrb.com/docs/usage/)
