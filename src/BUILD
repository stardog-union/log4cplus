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
    copts = ["-DINSIDE_LOG4CPLUS=1", "-DLOG4CPLUS_BUILD_DLL", "-D_DLL"],
    visibility = ["//visibility:public"],
)
