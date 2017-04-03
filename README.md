# CodeMirror PF Extensions Fork

### Quickstart

To build the project, make sure you have Node.js installed (at least version 6)
and then `npm install`. To run, just open `index.html` in your
browser (you don't need to run a webserver). Run the tests with `npm test`.

### Compress JS

Make sure you run `npm install uglify-js` then run `npm run compress`.  
This will compress all the files in uglify-config.js in order into ./lib/codemirror.all.js.

### Freemarker Mode

This build contains a custom Freemarker mode template modified from https://github.com/liuxiaole/codemirror-mode-freemarker

### Sync with upstream CodeMirror

1. $ git fetch upstream
2. $ git checkout master
3. $ git merge upstream/master
4. $ git push origin master
