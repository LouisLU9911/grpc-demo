load("@com_github_bazelbuild_buildtools//buildifier:def.bzl", "buildifier")

filegroup(
    name = "all",
    srcs = [
        "//src/client",
        "//src/server",
    ],
)

test_suite(
    name = "all_tests",
    tests = [],
)

filegroup(
    name = "gazelle",
    srcs = [
        "//src/client:gazelle",
        "//src/server:gazelle",
    ],
)

buildifier(
    name = "buildifier",
)
