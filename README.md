# kfs-db

## What's Here

### kfs-db/kfs-db/db-impex/
Database import/export tool used to create the needed database schema and load the base data for KFS. Currently, Oracle 10g+ and MySQL 5.1+ are supported.

### kfs-db/kfs-db/
Base directory for the demonstration and bootstrap datasets for KFS.

### kfs-db/kfs-db/demo/
Demo dataset useful for a quick start with enhancing or demonstrating the application without having to develop your data imports first.

### kfs-db/kfs-db/bootstrap/
An almost completely empty database except for base configuration and reference data. Use this when you are ready to import your institution's data.

### kfs-db/kfs-db/rice/
A clean rice server database onto which either of the above datasets can be overlaid if you will be running with Rice bundled into the KFS application.
