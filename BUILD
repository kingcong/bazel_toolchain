filegroup(
    name = "srcs",
    srcs = glob(["**"]),
    visibility = ["//tensorflow/bazel_toolchain:__pkg__"],
)

cc_binary(
    name = "hello",
    srcs = ["hello.cc"],
    deps = [
        "//tensorflow/cc:cc_ops",
        "//tensorflow/cc:client_session",
        "//tensorflow/core:tensorflow",
    ],
)
