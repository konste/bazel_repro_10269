workspace(name = "Repro_10269")

load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "boost",
    build_file = "@//thirdparty:boost/boost.BUILD",
    sha256 = "85a94ac71c28e59cf97a96714e4c58a18550c227ac8b0388c260d6c717e47a69",
    urls = ["https://dl.bintray.com/boostorg/release/1.71.0/source/boost_1_71_0.zip"],
)

http_archive(
    name = "icu65",
    build_file = "@//thirdparty:icu65/icu65.BUILD",
    sha256 = "cfaf7477d65272e9e01c739951f0607642c0510235e46befc109f6a3addd4f43",
    urls = ["https://github.com/unicode-org/icu/releases/download/release-65-1/icu4c-65_1-Win64-MSVC2017.zip"],
)
