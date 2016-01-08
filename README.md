## Thrift

This builds a `thrift` image using our fork. It's used in the thrift
files repo to generate the committed code.

The docker image is built using [automated builds][] on Docker hub.
Simply push to the master branch to build `saltside/thrift:latest` or
push a tag (e.g `0.9.2`) to build `saltide/thrift:0.9.2`.

Automation is linked with the automation user (github & docker hub in
this case).
