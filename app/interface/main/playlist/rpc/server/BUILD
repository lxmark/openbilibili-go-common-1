package(default_visibility = ["//visibility:public"])

load(
    "@io_bazel_rules_go//go:def.bzl",
    "go_library",
)

go_library(
    name = "go_default_library",
    srcs = ["rpc.go"],
    importpath = "go-common/app/interface/main/playlist/rpc/server",
    tags = ["automanaged"],
    visibility = ["//visibility:public"],
    deps = [
        "//app/interface/main/playlist/conf:go_default_library",
        "//app/interface/main/playlist/model:go_default_library",
        "//app/interface/main/playlist/service:go_default_library",
        "//library/net/rpc:go_default_library",
        "//library/net/rpc/context:go_default_library",
    ],
)

filegroup(
    name = "package-srcs",
    srcs = glob(["**"]),
    tags = ["automanaged"],
    visibility = ["//visibility:private"],
)

filegroup(
    name = "all-srcs",
    srcs = [":package-srcs"],
    tags = ["automanaged"],
    visibility = ["//visibility:public"],
)
