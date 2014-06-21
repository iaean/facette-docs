---
title: "Using Facette"
section: "docs"
groups:
   - "docs"
groups_weight: 30
---

# Using Facette

Once built, please make sure either the `facette` binary is available in your `PATH` or provide the full path to the
binary.

```
$ facette -h
Usage: facette [OPTIONS]

Options:
   -L  logging level
   -c  configuration file path
   -h  display this help and exit
   -l  log file path
```

Available logging levels:

 * `error`
 * `warning` (default)
 * `notice`
 * `info`
 * `debug`

To run the server, simply execute the command:

```
facette -c path/to/facette.json
```

<span class="fa fa-info-circle"></span> If the path to the configuration file is omitted, the default
`/etc/facette/facette.json` one will be loaded. If the path to log file is omitted, output will be written to *stderr*.