package(
    default_visibility = ["//visibility:public"],
)

cc_library(
    name = "radam",
    srcs = [
        "radam.cc",
    ],
    hdrs = [
        "radam.h",
    ],
    deps = [
        "//radish/utils:logging",
        "//radish/utils:tensor_util",
        "@com_google_absl//absl/strings",
    ],
)

cc_binary(
    name = "test_radam",
    srcs = ["test_radam.cc"],
    copts = [],
    deps = [
        ":lamb",
        ":radam",
    ],
)

cc_library(
    name = "lamb",
    srcs = [
        "lamb.cc",
    ],
    hdrs = [
        "lamb.h",
    ],
    deps = [
        "//radish/utils:logging",
        "//radish/utils:tensor_util",
        "@com_google_absl//absl/strings",
    ],
)