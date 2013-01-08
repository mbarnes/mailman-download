mailman-download
================

This script downloads all the archives for a set of mailing lists so
that you can maintain a local, searchable copy in a mail program like
Thunderbird.  The entire date range supplied will be combined into
a single archive file.

The configuration is driven from a simple YAML file that specifies your
mailman server as well as the lists and authentication (if needed) to
use.  The config file defaults to lists.yaml and can be overridden as
needed.

The script should be safely re-runnable and will download incremental
updates, only rebuilding the archive files if necessary.

Thunderbird
===========

This script has only been tested on Thunderbird, inspired by the
following blog post -
http://johnpoelstra.com/importing-mailing-list-archives-to-thunderbird/

After running this script, you will need to restart Thunderbird
and the archives will show up under your local folders.

Enjoy!
