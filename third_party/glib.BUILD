package(default_visibility = ["//visibility:public"])

cc_library(
    name = "glib",
    srcs = glob([
      "include/glib-2.0/gio/**",
      "include/glib-2.0/glib/**",
      "include/glib-2.0/gobject/**",
    ]),
    hdrs = glob([
      "include/glib-2.0/*.h",
      "lib/glib-2.0/include/*.h",
    ]),
    includes = [
      "include/glib-2.0",
      "lib/glib-2.0/include",
    ],
    linkopts = [
        "-lglib-2.0",
        "-lgobject-2.0",
        "-lgio-2.0",
        "-lgthread-2.0",
        "-L/usr/local/opt/glib/lib",
    ],
)
