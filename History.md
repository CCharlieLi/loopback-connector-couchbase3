
0.3.0 / 2016-08-03
==================

  * Merge pull request #1 from CCharlieLi/change-find-and-remove-return-count
  * update find/multiFind, destroy/multiDestroy to return array/count instead of throwing a error when instance does not exist
  * update couchbase to 2.2.1
  * Improved styles for the tests.
  * Improved some coding style.
  * Merge pull request #32 from Wiredcraft/greenkeeper-es6-shim-0.35.0
  * chore(package): update es6-shim to version 0.35.0
  * Use env var for Couchbase user and pass.
  * Updated JSCS and other packages.

0.2.2 / 2016-02-01
==================

  * Release 0.2.2
  * Merge pull request #30 from Wiredcraft/feature/ping
  * change test bucket name to test_ping
  * add clusterManager() method and test case for bucket crashed
  * add ping method
  * Satisfy JSCS 2.9.
  * Fixed coding styles.

0.2.1 / 2015-12-30
==================

  * Release 0.2.1
  * Fixed that the generated ID wasn't set back to model instance.
  * Update README.md
  * Setting up coveralls.io

0.2.0 / 2015-12-18
==================

  * Release 0.2.0.
  * Reviewed all CRUD methods, but disabled bulk operations for now.
  * Fix Node 0.12 doesn't have a proper `Object.assign()` with es6-shim.
  * Reviewed CRUD for all the single instance operations.
  * Merge pull request #22 from Wiredcraft/greenkeeper-should-8.0.0
  * chore(package): update should to version 8.0.0
  * CI doesn't need a special config.
  * CI doesn't need a special config.
  * Changed test bucket name.
  * Fixed the create hook and use CAS as rev.
  * Update dependencies.
  * Resorted functions and put the bulk operations together.
  * Save a `_type` with the doc which is the model name.
  * Removed some debugs that would slow it down.
  * Simpler way of getting a container ip.

0.1.0 / 2015-11-10
==================

  * Release 0.1.0
  * Small tweaks, for how we use promise etc.
  * Merge pull request #21 from CCharlieLi/updateTestAndCRUD
  * divide tests in separate describe
  * Add tests for save() and destroy()
  * update updateOrCreate() method and find() test
  * Setting up Travis.
  * API change: rebuilt view API and it now only uses promise (dropped callback).
  * Added bucket manager API.
  * Rebuilt connect() and disconnect().
  * Merge pull request #19 from Wiredcraft/update-example
  * Update example
  * Update example
  * Implemented updateOrCreate(), save(), destroy(). Reviewed create().
  * Update example

0.0.1 / 2015-10-20
==================

  * Release 0.0.1
  * Merge pull request #15 from Wiredcraft/module-uuid
  * Update for code standard check
  * Add api for view query
  * benchmark for crud function
  * Merge pull request #18 from CCharlieLi/master
  * update .jscsrc
  * update .jscsrc
  * sort jscs rules by letter
  * add .jscsrc
  * Merge pull request #17 from CCharlieLi/master
  * jscs check with .jscsrc
  * Merge pull request #14 from CCharlieLi/module-uuid
  * update CRUD methods
  * Merge pull request #10 from WXGBridgeQ/master
  * Update .npmignore
  *  add uuid for  generate id and rewrite test case for CRUD
  * Update .npmignore
  * add example https://github.com/Wiredcraft/loopback-connector-couchbase3/issues/8
  * Merge pull request #6 from CCharlieLi/master
  * update readme
  * add another test data model which include array type, update CURD tests
  * add create,update,destroy's error test
  * lost a semicolon after promisifyAll()
  * deploy promisifyAll() into connect()
  * update promise handle
  * update CRUD methods, remove catch and update promise chain
  * add annotation
  * add TypeError exception handler
  * update Readme
  * add and update CRUD methods and tests
  * add exists,find method and test
  * add create method
  * update readme, add debug info & init config to run test
  * Added tests for connect and disconnect.
  * Added the class with connect and disconnect.
  * Basic files.
  * Initial commit

