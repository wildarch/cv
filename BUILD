load("@bazel_latex//:latex.bzl", "latex_document")

latex_document(
    name = "cv",
    srcs = [
        "main.tex",
        "@bazel_latex//packages:geometry",
        "@bazel_latex//packages:moderncv",
    ],
    main = "main.tex",
)
