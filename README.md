s3swap
======

Management of multiple s3cmd configs and aws credentials.

Setup Instructions
------------------

* Install s3cmd; you can do it via brew or apt-get, or manually from their site: http://s3tools.org/s3cmd
* Configure by running `s3cmd --configure`; you'll be prompted for your AWS credentials
* Your config is now in ~/.s3cfg -- move it to a named config: `mv ~/.s3cfg-name`
* Put a symlink to `s3swap` from this repo to a directory in your `PATH`; I use `~/bin`

Usage Instructions
------------------

To change credentials, run `s3swap configname`
