cc_binary(
    name = "igdumpstats",
    srcs = ["bin/igdumpstats.cpp"],
    deps = [
        ":IgFiles"
    ]
)

cc_library(
    name = "IgFiles",
    srcs = glob(["src/*.cc", "src/*.c"]),
    hdrs = glob(["src/*.h"]),
    includes = ["src"],
    visibility = ["//visibility:public"]
)
