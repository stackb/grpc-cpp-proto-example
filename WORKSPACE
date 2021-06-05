# -- CHUNK for stackb/rules_proto --

load(
    "//:repositories.bzl",
    "build_stack_rules_proto",
    "rules_proto",
    com_github_grpc_grpc_deps = "grpc_deps",
)

rules_proto()

build_stack_rules_proto()

com_github_grpc_grpc_deps()

register_toolchains("@build_stack_rules_proto//toolchain")

# -- CHUNK for grpc/grpc --

load(
    "@com_github_grpc_grpc//bazel:grpc_deps.bzl",
    "grpc_deps",
)

grpc_deps()
