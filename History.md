1.1.0 / 2015-03-24
=================
  
  * Modern rewrite of parser and file finder
  * Finder now excludes node_modules directory and minified javascript
  * Updated tests to reflect new parser (Esprima)

1.0.0 / 2012-02-26 
==================

  * Added 0.6.x support

0.0.6 / 2011-08-15 
==================

  * Added `commander` dependency
  * Changed stats(1) to use the commander module
  * Fixed error messages for files not found (now throwing)

0.0.5 / 2011-08-03 
==================

  * Added shebang support

0.0.4 / 2011-08-03 
==================

  * Removed uglifyjs dep (inlined)
  * Fixed single-file stats [saschagehlich]
  * Fixed top-level returns
  * Fixed: show help when no args are present [criso]

0.0.3 / 2011-08-03 
==================

  * Fixed mutation of first file's stats

0.0.2 / 2011-08-03 
==================

  * Added `-I, --ignore-errors`
  * Fixed uglify error handling

0.0.1 / 2010-01-03
==================

  * Initial release
