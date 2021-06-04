load("//:repositories.bzl", "rules_proto", "build_stack_rules_proto", "protobuf_deps")

rules_proto()

build_stack_rules_proto()

protobuf_deps()

register_toolchains("@build_stack_rules_proto//toolchain")
