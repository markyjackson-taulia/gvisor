package(licenses = ["notice"])  # BSD

load("@io_bazel_rules_go//go:def.bzl", "go_library")

go_library(
    name = "rawfile",
    srcs = [
        "blockingpoll_amd64.s",
        "errors.go",
        "rawfile_unsafe.go",
    ],
    importpath = "gvisor.googlesource.com/gvisor/pkg/tcpip/link/rawfile",
    visibility = [
        "//visibility:public",
    ],
    deps = ["//pkg/tcpip"],
)
