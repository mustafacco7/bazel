licenses(["notice"])

filegroup(
    name = "srcs",
    srcs = glob(["**"]),  # glob everything to satisfy the compile.sh srcs test
    visibility = ["//third_party:__pkg__"],
)

exports_files([
    "BUILD",
    "proto_info_bzl_deps.patch",
    "remove_rules_rust.patch",
    "add_python_loads.patch",
    "add_rules_shell_loads.patch",
    "bzl_library.patch",
])

alias(
    name = "protoc",
    actual = "@protobuf//:protoc",
    visibility = ["//visibility:public"],
)

alias(
    name = "protobuf_java",
    actual = "@protobuf//:protobuf_java",
    visibility = ["//visibility:public"],
)

alias(
    name = "protobuf_java_util",
    actual = "@protobuf//:protobuf_java_util",
    visibility = ["//visibility:public"],
)

alias(
    name = "protobuf_python",
    actual = "@protobuf//:protobuf_python",
    visibility = ["//visibility:public"],
)

alias(
    name = "protoc_lib",
    actual = "@protobuf//:protoc_lib",
    visibility = ["//visibility:public"],
)
