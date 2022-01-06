package(default_visibility = ["//visibility:public"])

cc_library(
    name = "zip",
    hdrs = ["zip.h", "zipconf.h"],
    includes = ["."],
    linkopts = [
      "-lzip",
      "-L/usr/local/opt/libzip/lib",
    ],
)
