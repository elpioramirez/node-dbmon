1.0.3 / 2011-10-26
==================
  * Added the filesystem driver and the inotifywait method; filesystem database emulation to have real-time file change notification using inotifywait child_process
  * Test bugfix and refactoring

1.0.2 / 2011-10-25
==================

  * Added the possibility to notify not only if something changes, but also what have changed, see channelDefaults.keyfld
  * Added the truncate monitoring via TRIGGER for postgresql driver

1.0.1 / 2011-10-24
==================

  * Initial release
  * Added PostgreSQL driver with TRIGGER and LISTEN/NOTIFY support added
  * Added Console and EventEmitter transports

1.0.0 / 2011-10-22
==================

  * Idea