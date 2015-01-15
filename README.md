##General
Site is written using [Grunt](http://gruntjs.com/) as a task runner and the [Sass](http://sass-lang.com) preprocessor for CSS. Everything else is pretty straight forward. 

##Setting the up environment
1. Download [Git](http://git-scm.com/downloads) if you don't already have it installed, then clone this repository to your desktop.
2. Download and install [Node.js](http://nodejs.org/)
3. Open terminal, navigate to project directory, then run `npm install` to install dependencies
4. (Optional) Download [Livereload](https://chrome.google.com/webstore/detail/livereload/jnihajbhpnppcggbcgedagnkighmdlei?hl=en) if you want to enable live reloading of your dev site without having to refresh the page.

##Running project on local host
1. Open terminal, navigate to project directory, and run `grunt` to compile Sass file and then `grunt dev` to run project on localhost:8000.
2. Run `grunt` in terminal any time you've made an update in a Sass file to compile into CSS.
