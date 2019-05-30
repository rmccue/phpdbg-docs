---
title: Usage
parent: Legacy Site
---

# Command Line Usage

The following switches are implemented (just like cli SAPI):

* -n ignore php ini
* -c search for php ini in path
* -z load zend extension
* -d define php ini entry

The following switches change the default behaviour of phpdbg:

* -v disables quietness
* -s enabled stepping
* -e sets execution context
* -b boring - disables use of colour on the console
* -I ignore .phpdbginit (default init file)
* -i override .phpgdbinit location (implies -I)
* -O set oplog output file
* -q do not print banner on startup
* -r jump straight to run
* -E enable step through eval()

Note: passing -rr will cause phpdbg to quit after execution, rather than returning to the console
