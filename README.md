# sreplace
A bash find string and replace script

    usage: sreplace [OPTIONS] PATTERN STRING

    Find and replace string against all files within a given path.
    Logs output for diff comparison.

    OPTIONS:
        -h      Show this message
        -p      Path to search (default is PWD)
        -d      Depth of directory search (integer)