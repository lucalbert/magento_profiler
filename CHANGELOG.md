CHANGELOG
=========

next version 
-----
* fix for #1 Not working in secure environnement with magento 1.9.2 (https://)
* fix for #6 Undefined index error in layout data collector 
* added magento 1.9.3 to test stack

1.2.0
-----
* fixed an exception in debug mode when block output is suppressed with "disable module output"
* fixed an exception when logging and monolog is not installed
* unified call stack rendering
* improved request collector to capture also redirects, session data and flash messages
* improved support for "xdebug.file_link_format" to also work with urls like "http://localhost:63342/api/file/%f:%l"

1.1.0
-----
* improved logger, will now also display deprecations
* added unit tests
* small toolbar adjustments
* general clean up
* cleaned up overwrite logic

1.0.1
-----

* added the new "model" collector
* minor improvements into the documentation
* small stability fixes
* improved event data collector + display, now also showing the observers 
* added clear/enable/disable caches actions to the toolbar
