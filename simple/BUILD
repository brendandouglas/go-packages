package(default_visibility = ["//visibility:public"])

load("@io_bazel_rules_go//proto:go_proto_library.bzl", "go_proto_library")
load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_proto_library(
    name = "foo_go_proto",
    srcs = ["foo.proto"],
)

go_library(
    name = "simple",
    srcs = [
        "duration.go",
        "other_dir/other.go",
    ],
    importpath = "simple",
    deps = [":foo_go_proto"],
)
