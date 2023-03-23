load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "bazel_latex",
    sha256 = "188d071c58aae710327840dfd5d26691620815ced81ba220df4f675bad40dfed",
    strip_prefix = "bazel-latex-8cb1159501597afce9be1d78e38ef7ef5d91400a",
    url = "https://github.com/ProdriveTechnologies/bazel-latex/archive/8cb1159501597afce9be1d78e38ef7ef5d91400a.zip",
)

register_toolchains(
    "@bazel_latex//:latex_toolchain_aarch64-darwin",
    "@bazel_latex//:latex_toolchain_amd64-freebsd",
    "@bazel_latex//:latex_toolchain_x86_64-darwin",
    "@bazel_latex//:latex_toolchain_x86_64-linux",
)

load("@bazel_latex//:repositories.bzl", "latex_repositories")

latex_repositories()

http_archive(
    name = "rules_python",
    sha256 = "a644da969b6824cc87f8fe7b18101a8a6c57da5db39caa6566ec6109f37d2141",
    strip_prefix = "rules_python-0.20.0",
    url = "https://github.com/bazelbuild/rules_python/releases/download/0.20.0/rules_python-0.20.0.tar.gz",
)

load("@rules_python//python:repositories.bzl", "py_repositories")

py_repositories()
