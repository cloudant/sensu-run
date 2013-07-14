sensu-run
=========

Execute sensu checks locally on demand. 

Usage
========

To use the tool, run the senu-run command and pass check name(s) as parameters. 

```bash
    sensu-run load-avg memory-usage
```

**NOTE** bash completion is available, so you can `TAB` your way to find the check name(s) you want to run

Installation
============

1. Copy `sensu-run` to a directory thats in your path (eg /usr/bin)

```bash
    cp sensu-run /usr/bin
```
2. Copy `sensu-run.bash_completion` to `/etc/bash_completion.d`

```bash
    cp sensu-run.bash_completion /etc/bash_completion.d
```

TODO
===========

Packagize this project into deb/rpm/etc
