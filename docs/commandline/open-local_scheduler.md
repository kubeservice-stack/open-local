## open-local scheduler

scheduler is a scheduler extender implementation for local storage

### Synopsis

scheduler provides the capabilities for scheduling cluster local storage as a whole

```
open-local scheduler [flags]
```

### Options

```
      --enabled-node-anti-affinity string   whether enable node anti-affinity for open-local storage backend, example format: 'MountPoint=5,LVM=3'
  -h, --help                                help for scheduler
      --kubeconfig string                   Path to the kubeconfig file to use.
      --master string                       URL/IP for master.
      --port int32                          Port for receiving scheduler callback, set to '0' to disable http server
      --scheduler-strategy string           Scheduler Strategy: binpack or spread (default "binpack")
```

### Options inherited from parent commands

```
      --add-dir-header                   If true, adds the file directory to the header of the log messages
      --alsologtostderr                  log to standard error as well as files
      --log-backtrace-at traceLocation   when logging hits line file:N, emit a stack trace (default :0)
      --log-dir string                   If non-empty, write log files in this directory
      --log-file string                  If non-empty, use this log file
      --log-file-max-size uint           Defines the maximum size a log file can grow to. Unit is megabytes. If the value is 0, the maximum file size is unlimited. (default 1800)
      --log-flush-frequency duration     Maximum number of seconds between log flushes (default 5s)
      --logtostderr                      log to standard error instead of files (default true)
      --one-output                       If true, only write logs to their native severity level (vs also writing to each lower severity level)
      --skip-headers                     If true, avoid header prefixes in the log messages
      --skip-log-headers                 If true, avoid headers when opening log files
      --stderrthreshold severity         logs at or above this threshold go to stderr (default 2)
  -v, --v Level                          number for the log level verbosity
      --vmodule moduleSpec               comma-separated list of pattern=N settings for file-filtered logging
```

### SEE ALSO

* [open-local](./open-local.md)	 - 

