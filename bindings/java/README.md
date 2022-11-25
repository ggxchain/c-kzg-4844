# Build Shared Library

## Prerequisites

* Follow the instructions in the [README.md](../../README.md) to install blst and build the C-KZG code.
* `JAVA_HOME` environment variable is set to a JDK with an `include` folder containing a jni.h file.

## Build
```bash
make build
```

This will install the library in the `src/main/resources/lib` folder according to your OS

## Test
```bash
make test
```