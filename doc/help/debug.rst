
.. code::

    $ coverage debug --help
    Usage: coverage debug <topic>
    
    Display information about the internals of coverage.py, for diagnosing
    problems. Topics are: 'data' to show a summary of the collected data; 'sys' to
    show installation information; 'config' to show the configuration; 'premain'
    to show what is calling coverage.
    
    Options:
      --debug=OPTS     Debug options, separated by commas. [env: COVERAGE_DEBUG]
      -h, --help       Get help on this command.
      --rcfile=RCFILE  Specify configuration file. By default '.coveragerc',
                       'setup.cfg', 'tox.ini', and 'pyproject.toml' are tried.
                       [env: COVERAGE_RCFILE]
    
