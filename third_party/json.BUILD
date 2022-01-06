package(default_visibility = ["//visibility:public"])

cc_library(
    name = "json",
    hdrs = glob(["json/*.h"]),
    includes = ["."],
    linkopts = [
      "-ljsoncpp",
      "-L/usr/local/opt/jsoncpp/lib",
    ],
)

