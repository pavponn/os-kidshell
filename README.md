# Kidshell
Kidshell is a simple POSIX shell, written in C++.
This is an educational project, aimed at understanding how to interact with a POSIX-compatible API to launch child processes.

## Main Features
* Basic executable launch and wrapping
* Limited environment variables support
* Built-in commands: export, unset, exit

### Environmental variables
`export` or `export -p` or `env` - show all environmental variables

`export VAR1=VALUE1 VAR2=VALUE2 ...` - export variable (multiple variables)

`unset VAR1 VAR2 ...`  - unset variable (multiple variables)

## 

## Build
```
$ mkdir build
$ cd build
$ cmake ..
$ make
```
Requires C++11 compiler

## Test
Tested manually on macOS Mojave 10.14.3 and Linux 4.12.

## Copyright
Pavel Ponomarev, 2019 (pavponn@gmail.com)
MIT License.





