package(default_visibility = ["//visibility:public"])

cc_library(
    name = "gts",
    hdrs = glob(["*.h"]),
    includes = ["."],
    linkopts = [
      "-lgts",
      "-lm",
      "-L/usr/local/opt/gts/lib"
    ],
    deps = [
      "@glib"
    ]
)
