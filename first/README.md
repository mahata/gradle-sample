To run the `hello` task:

```
$ gradle hello
```

To run the task & daemonize the gradle process:

```
$ gradle --daemon hello
Starting a new Gradle Daemon for this build (subsequent builds will be faster).
:hello
Hello Gradle world!

BUILD SUCCESSFUL

Total time: 2.707 secs

$ gradle --daemon hello
:hello
Hello Gradle world!

BUILD SUCCESSFUL

Total time: 0.526 secs
```

2nd run is much faster because there's a gradle daemon.
