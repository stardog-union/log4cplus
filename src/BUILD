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
    #defines = ["LOG4CPLUS_BUILD_DLL", "_DLL", "LOG4CPLUS_DISABLE_TRACE", "LOG4CPLUS_DISABLE_DEBUG", "LOG4CPLUS_DISABLE_INFO", "LOG4CPLUS_DISABLE_WARN", "LOG4CPLUS_DISABLE_ERROR", "LOG4CPLUS_DISABLE_FATAL"],
    visibility = ["//visibility:public"],
)
