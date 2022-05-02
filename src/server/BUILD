load("@io_bazel_rules_go//go:def.bzl", "go_binary", "go_library")
load("@bazel_gazelle//:def.bzl", "gazelle")

package(default_visibility = ["//visibility:public"])

# gazelle:prefix github.com/LouisLU9911/grpc-demo/server
gazelle(name = "gazelle")

go_library(
    name = "server_lib",
    srcs = ["main.go"],
    importpath = "github.com/LouisLU9911/grpc-demo/server",
    visibility = ["//visibility:private"],
)

go_binary(
    name = "server",
    embed = [":server_lib"],
    visibility = ["//visibility:public"],
)
