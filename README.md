fwcontrol
=========

A simple script to control FreeBSD ipfw firewall.

Usage: $name [-h] [-n] [-r] [-t [<list of tables>]]

  -h    Show this help and exit
  -n    Dry run: just check a syntax
  -r    Reload rules
  -t    Reload tables (all or from specifyed list)

To test your rules just run the script with -n switch, it will test
the syntax and rules and immediately exit in case of error.
