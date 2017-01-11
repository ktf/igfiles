cc_test(
    name = "test_igfiles",
    srcs = glob(["test_igfiles-*.cpp","test_igfiles-*.h"]),
    linkopts = ["-lz"],
    deps = [
        "//:IgFiles"
    ]
)

cc_test(
    name = "test_StyleParser",
    srcs = glob(["test_StyleParser*.cpp","test_StyleParser*.h"]),
    linkopts = ["-lz"],
    data = ["data/default-style.iss"],
    deps = [
        "//:IgFiles"
    ]
)

