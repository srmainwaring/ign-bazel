package(default_visibility = ["//visibility:public"])

cc_library(
    name = "zmq",
    hdrs = ["zmq.h", "zmq_utils.h"],
    includes = ["."],
    linkopts = [
      "-lzmq",
      "-L/usr/local/opt/zeromq/lib",
    ],
    deps = [
      "@cppzmq",
    ]
)
