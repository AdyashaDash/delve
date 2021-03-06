## dlv test

Compile test binary and begin debugging program.

### Synopsis


Compiles a test binary with optimizations disabled and begins a new debug session.

The test command allows you to begin a new debug session in the context of your
unit tests. By default Delve will debug the tests in the current directory.
Alternatively you can specify a package name, and Delve will debug the tests in
that package instead.

```
dlv test [package]
```

### Options inherited from parent commands

```
      --accept-multiclient[=false]: Allows a headless server to accept multiple client connections. Note that the server API is not reentrant and clients will have to coordinate.
      --api-version=1: Selects API version when headless.
      --build-flags="": Build flags, to be passed to the compiler.
      --headless[=false]: Run debug server only, in headless mode.
      --init="": Init file, executed by the terminal client.
  -l, --listen="localhost:0": Debugging server listen address.
      --log[=false]: Enable debugging server logging.
      --wd=".": Working directory for running the program.
```

### SEE ALSO
* [dlv](dlv.md)	 - Delve is a debugger for the Go programming language.

###### Auto generated by spf13/cobra on 15-Feb-2017
