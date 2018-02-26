Command Line Options
====================

These flags allow you to change the behavior of Crawler. Check out how to use them in the :doc:`cookbook`.

.. option:: -d <sec>, --delay <sec>

  Use a delay in between page fetchs so we don't overwhelm the remote server. Value in seconds.

  Default: 1 second
    
.. option:: -i <regex>, --ignore <regex>

  Ignore pages that match a specific pattern.

  Default: None

Have a look at http://sphinx-argparse.readthedocs.io/en/latest/index.html for this! :)
