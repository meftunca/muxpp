load("@rules_cc//cc:defs.bzl", "cc_library")

cc_library(
    name = "mux",
    hdrs = glob(["*.hpp"]),
    # -lpthread
    linkopts = [
        "-pthread",
        "-L/opt/homebrew/opt/gperftools/lib",
    ],
    visibility = ["//visibility:public"],
    deps = [
        "//ada",
        "//taskflow",
    ],
)
