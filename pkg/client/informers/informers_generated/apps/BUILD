package(default_visibility = ["//visibility:public"])

licenses(["notice"])

load(
    "@io_bazel_rules_go//go:def.bzl",
    "go_binary",
    "go_library",
    "go_test",
    "cgo_library",
)

go_library(
    name = "go_default_library",
    srcs = ["interface.go"],
    tags = ["automanaged"],
    deps = [
        "//pkg/client/informers/informers_generated/apps/internalversion:go_default_library",
        "//pkg/client/informers/informers_generated/apps/v1beta1:go_default_library",
        "//pkg/client/informers/interfaces:go_default_library",
    ],
)
