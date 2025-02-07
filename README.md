# bull-repl

Bull queue command line REPL.

```
npm install bull-repl -g
bull-repl
help
```

```
  Commands:

    help [command...]          Provides help for a given command.
    exit                       Exits application.
    connect [options] <queue>  connect to bull queue
    stats                      count of jobs by groups
    active [options]           fetch active jobs
    waiting [options]          fetch waiting jobs
    completed [options]        fetch completed jobs
    failed [options]           fetch failed jobs
    delayed [options]          fetch delayed jobs
    pause                      pause current queue
    resume                     resume current queue from pause
    get <jobId...>             get job
    add [options] <data>       add job to queue
    rm <jobId...>              remove job
    retry <jobId...>           retry job
    retry-failed               retry all failed jobs
    promote <jobId...>         promote job
    fail <jobId> <reason>      fail job
    complete <jobId> <data>    complete job
    clean [options] <period>   Clean queue for period ago, period format - ms
                               (​https://github.com/zeit/ms#examples​)
    logs [options] <jobId>     get logs of job
    log <jobId> <data>         add log to job
```

### Note

You can see help on each command, for example: `connect --help`
