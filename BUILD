load("@com_github_bazelbuild_buildtools//buildifier:def.bzl", "buildifier")

buildifier(
    name = "buildifier",
)

filegroup(
    name = "gazelle",
    srcs = [
        "//src/client/gazelle",
        "//src/server/gazelle",
    ],
)
