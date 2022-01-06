package(default_visibility = ["//visibility:public"])

cc_library(
    name = "yaml",
    srcs = glob([
      "yaml-cpp/node/*.h",
      "yaml-cpp/node/detail/*.h",
    ]),
    hdrs = glob([
      "yaml-cpp/*.h",
    ]),
    includes = [
      ".",
      "yaml-cpp",
    ],
    linkopts = [
      "-lyaml-cpp",
      "-L/usr/local/opt/yaml-cpp/lib",
    ],
)
