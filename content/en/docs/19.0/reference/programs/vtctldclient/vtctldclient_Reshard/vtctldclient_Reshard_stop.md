---
title: Reshard stop
series: vtctldclient
commit: 0f751fbb7c64ca5280c5d4f58d038e1df5477c67
---
## vtctldclient Reshard stop

Stop a Reshard workflow.

```
vtctldclient Reshard stop
```

### Examples

```
vtctldclient --server localhost:15999 Reshard --workflow cust2cust --target-keyspace customer stop
```

### Options

```
  -h, --help   help for stop
```

### Options inherited from parent commands

```
      --action_timeout duration   timeout to use for the command (default 1h0m0s)
      --compact                   use compact format for otherwise verbose outputs
      --format string             The format of the output; supported formats are: text,json. (default "text")
      --server string             server to use for the connection (required)
      --target-keyspace string    Target keyspace for this workflow.
  -w, --workflow string           The workflow you want to perform the command on.
```

### SEE ALSO

* [vtctldclient Reshard](../)	 - Perform commands related to resharding a keyspace.
