## packet capactiy check

Validates if a deploy can be fulfilled.

### Synopsis

Example:

packet capacity check -f [facility] -p [plan] -q [quantity]

	

```
packet capactiy check [flags]
```

### Options

```
  -f, --facility string   Code of the facility
  -h, --help              help for check
  -j, --json              JSON output
  -p, --plan string       Name of the plan
  -q, --quantity int      Number of devices wanted
  -y, --yaml              YAML output
```

### Options inherited from parent commands

```
      --config string   Path to JSON or YAML configuration file
```

### SEE ALSO

* [packet capactiy](packet_capactiy.md)	 - Capacities operations

###### Auto generated by spf13/cobra on 18-Dec-2019
