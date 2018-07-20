CloudEdit
####CloudEdit: A client side jsFiddle-like HTML Editor.

Supports HTML5/CSS3/jQuery1.x development.
Multiple themes and syntax highlighting thanks to ACE editor.
Download compiled file support for most browsers:
Concatenates html/css/js to their inline equivalents for single-file download.
Toggle-able editor panes resize automatically based upon how many are displayed.
Uses sessionStorage for the current state in case of the 'accidental' browser refresh.
Uses localStorage to store the currently selected theme for your next use.
Added:

- Rudimentary "view-only" JavaScript console for console.log statements.

Unfortunately I have no way of catching "undefined" variables. They still go to the Browser.
jqConsole from repl.it for complete js console.
Preview Modal in case you don't like scrolling or want more of the end-user experience.
Context menu on "right-click" over any editor pane.
Theme Chooser for editor windows (changes all).
JS and CSS Imports for the preview window. Currently:
autoprefixer.js
modernizr.js
normalize.css
LESS.css
SASS.css : Experimental. The minified js is 2 Megabytes!
Frameworks:
Bootstrap 3 CSS & JS
Foundation CSS & JS
Downloaded HTML file now includes CDN versions of selected JS/CSS Imports as well as autoprefixing all embedded CSS if autoprefixer chosen as an import.
Appcache manifest for offline caching of resources and quicker future loading.
Save current session to localStorage for persistence.
Load previous session from localStorage into current panes.
Image1

Image2
