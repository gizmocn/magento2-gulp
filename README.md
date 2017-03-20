/* ===========================
   Comparing with Grunt
   =========================== */
   
Compilation of all themes (10 files):

Gulp: 16sec

Grunt 33sec

Custom theme compilation (2 files):

Gulp: 4.5s

Grunt: 11.2s

/* ===========================
   Installation and how to use
   =========================== */
/*
 * 1. Install node.js for your OS: https://nodejs.org/en/
 * 2. Install modules: run a command in a root directory of your project "npm install"
 * 3. Run gulp command in the root directory with arguments or without. Examples:
 * 3.1. Compilation of all themes: gulp
 * 3.2. Compilation of certain theme: gulp less --luma
 * 3.3. Watcher of certain theme: gulp watch --luma
 * 3.3.1 Watcher with sourcemap: gulp watch --luma --map
 * 3.4. Compilation of certain theme with minification (+~2.5s): gulp less --luma --min
 * 3.5. Compilation of certain theme with sourcemap(+~1.5s), can't be used with minification: gulp less --luma --map
 * 3.6. Compilation with live reload: gulp less --luma --live
 * 3.7. Watcher with liveReload: gulp watch --luma --live
 * 4. For using liveReload install extension for your browser: http://livereload.com/
 * 4.1. Turn on the extension on the page of project.
 */
