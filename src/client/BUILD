load("@io_bazel_rules_go//go:def.bzl", "go_binary", "go_library")
load("@bazel_gazelle//:def.bzl", "gazelle")

package(default_visibility = ["//visibility:public"])

# gazelle:prefix github.com/LouisLU9911/grpc-demo/client
gazelle(name = "gazelle")

go_library(
    name = "client_lib",
    srcs = ["main.go"],
    importpath = "github.com/LouisLU9911/grpc-demo/client",
    visibility = ["//visibility:private"],
)

go_binary(
    name = "client",
    embed = [":client_lib"],
    visibility = ["//visibility:public"],
)
