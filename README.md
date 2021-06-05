# grpc-cpp-proto-example

Example repo for compiling C++ outputs for protobuf+gRPC


```bash
$ bazel build //proto:example_cpp_compile
Target //proto:example_cpp_compile up-to-date:
  bazel-bin/proto/example.pb.cc
  bazel-bin/proto/example.pb.h
  bazel-bin/proto/example.grpc.pb.cc
  bazel-bin/proto/example.grpc.pb.h
```
