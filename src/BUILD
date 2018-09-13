cc_library(
    name = "src",
    srcs = glob(["*.cxx"],
                exclude = [
		    "clfsappender.cxx",
		    "msttsappender.cxx",
		]),
    deps = [
        "//include",
        "//threadpool",
    ],
    copts = ["-DINSIDE_LOG4CPLUS=1"],
    visibility = ["//visibility:public"],
)
