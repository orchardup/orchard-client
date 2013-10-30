Change log
==========

1.0.3 – 2013-10-30
------------------

 - Volumes specified in a Dockerfile will now be created as volumes
   on Orchard. Previously, you had to specify them with a `-v` option
   to `docker run`.

1.0.2 – 2013-10-28
------------------

 - Indent output from `docker inspect`
 - Fix `docker run` outputting `Connection closed by server`
 - Add `-e` and `-p` options to `docker replace`
 - Add `logs()` method to Docker client

1.0.1 – 2013-10-04
------------------

 - Start container after attaching to it so as not to lose output
 - Add `--version` option to client

1.0.0 – 2013-10-01
------------------

 - Initial release