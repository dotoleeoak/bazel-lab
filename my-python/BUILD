load("@rules_python//python:defs.bzl", "py_library")
load("@deps//:requirements.bzl", "requirement")

py_library(
    name = "lib",
    srcs = glob(["*.py"]),
    deps = [
        # requirement("six"),
        requirement("autobahn"),
        # "@deps//autobahn",
    ],
)
