load("@bazel_tools//tools/build_defs/repo:http.bzl", "http_archive")

http_archive(
    name = "bazel_latex",
    sha256 = "073ef29bc6afd799c3fef6ec9e84b8caa1c417a86e7aa50aa07b502da309961b",
    strip_prefix = "bazel-latex-aa33f92fc7a0c93f7d19e2bae89123f30bdf3611",
    url = "https://github.com/ProdriveTechnologies/bazel-latex/archive/aa33f92fc7a0c93f7d19e2bae89123f30bdf3611.zip",
)

load("@bazel_latex//:repositories.bzl", "latex_repositories")

latex_repositories()
