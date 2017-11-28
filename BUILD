cc_library(
    name = "benchmark",
    srcs = glob(
        include = [
            "benchmark/src/*.cc"
        ],
        exclude = [
            "benchmark/src/re_posix.cc",
            "benchmark/src/gnuregex.cc",
        ],
    ),
    hdrs = glob(
        include = [
            "benchmark/src/*.h",
            "benchmark/include/benchmark/*.h",
        ],
        exclude = [
            "benchmark/src/re_posix.h",
            "benchmark/src/gnuregex.h",
        ],
    ),
    includes = [
         "benchmark/include",
    ],
    visibility = ["//visibility:public"],
    copts = [
          "-DHAVE_STD_REGEX",
    ],
)
