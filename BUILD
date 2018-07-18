load("@io_bazel_rules_go//go:def.bzl", "go_prefix", "go_test")

licenses(["unencumbered"])  # Google-owned

exports_files(["LICENSE"])

go_prefix("proctor/production/prober")

go_test(
    name = "frontend_staging",
    srcs = ["pass.go"],
)

go_test(
    name = "no_filter",
    srcs = ["pass.go"],
)

go_test(
    name = "ignore_only",
    srcs = ["pass.go"],
)
go_test(
    name = "include_only",
    srcs = ["pass.go"],
)
go_test(
    name = "both",
    srcs = ["pass.go"],
)
