load("@io_bazel_rules_go//go:def.bzl", "go_prefix", "go_test")

licenses(["unencumbered"])  # Google-owned

exports_files(["LICENSE"])

go_prefix("proctor/production/prober")

go_test(
    name = "pass",
    srcs = ["pass.go"],
)

go_test(
    name = "fail",
    srcs = ["fail.go"],
)

go_test(
    name = "broken",
    srcs = ["broken.go"],
)
