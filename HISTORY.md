
2.0.2 / 2015-01-05
==================

  * fix normalize bug in windows, fixes #29

2.0.1 / 2014-12-02
==================

  * accept abnormal path, like: //index.html

2.0.0 / 2014-11-14
==================

  * bump koa
  * only response GET and HEAD

1.2.0 / 2014-09-18
==================

  * bump compressible and mime-types
  * decodeURI when use this.path as key to fetch value from files object

1.1.0 / 2014-07-16
==================

  * replace mime by mime-types
  * remove onerror and destroy, let koa hanlde these stuff

1.0.10 / 2014-05-18
==================

  * bump fs-readdir-recursive, fixed #14
  * fix bad argument handling, fixed #20
  * should not return gzip buffer when accept encoding not include gzip

1.0.9 / 2014-03-31
==================

  * add url prefix option

1.0.8 / 2014-03-31
==================

  * support options.dir, default to process.cwd()
  * add vary, check file's length when gzip
  * Ensure files can be gzipped via compressible.

1.0.7 / 2014-03-26
==================

  * add options.gzip to control gzip, support stream's gzip
  * add gzip support for buffers

1.0.3 / 2014-01-14
==================

 * update `on-socket-error`

1.0.0 / 2013-12-21
==================

 * use `yield* next`
