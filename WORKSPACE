load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "bazel_latex",
    sha256 = "b4dd9ae76c570b328be30cdc5ea7045a61ecd55e4e6e2e433fb3bb959be2a44b",
    strip_prefix = "bazel-latex-0.16",
    url = "https://github.com/ProdriveTechnologies/bazel-latex/archive/v0.16.tar.gz",
)

load("@bazel_latex//:repositories.bzl", "latex_repositories")

latex_repositories()
