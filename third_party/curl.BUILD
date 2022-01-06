package(default_visibility = ["//visibility:public"])

cc_library(
    name = "curl",
    hdrs = glob(["curl/*.h"]),
    includes = ["."],
    linkopts = [
      "-lcurl",
      "-L/usr/local/opt/curl/lib",
    ],
)
