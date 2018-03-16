workspace(name = "go_packages")

rules_go_commit = "74d8ad8f9f59a1d9a7cf066d0980f9e394acccd7"

git_repository(
    name = "io_bazel_rules_go",
    commit = rules_go_commit,
    remote = "https://github.com/bazelbuild/rules_go",
)

load("@io_bazel_rules_go//go:def.bzl", "go_rules_dependencies", "go_register_toolchains", "go_repository")

go_rules_dependencies()

go_register_toolchains()

go_repository(
    name = "com_github_bazelbuild_rules_go",
    commit = rules_go_commit,
    importpath = "github.com/bazelbuild/rules_go",
)

go_repository(
    name = "com_github_golang_protobuf",
    commit = "130e6b02ab059e7b717a096f397c5b60111cae74",
    importpath = "github.com/golang/protobuf",
)

