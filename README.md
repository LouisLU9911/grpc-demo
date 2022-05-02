# gRPC Demo

This repo is a simple example about [gRPC](https://grpc.io) with [Bazel](https://bazel.build).

## Requirements

* Bazel 5.1.1 or higher version
* Go 1.18 (see [WORKSPACE](WORKSPACE))

## Build

```bash
bazel build //:all
```

## Test

```bash
bazel test //:all_tests
```

## Contribution

See the [CONTRIBUTING.md](CONTRIBUTING.md)
