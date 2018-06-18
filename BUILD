load("@io_bazel_rules_scala//scala:scala.bzl", "scala_library")
load("@io_bazel_rules_scala//scala:scala.bzl", "scala_test")

scala_library(
    name = "moztelemetry",
    srcs = glob(["src/**/*.scala"]),
    visibility = ["//visibility:public"]
)

scala_test(
  name = "test",
  srcs = glob(["src/test/*.scala"]),
  deps = ["moztelemetry"]
)
