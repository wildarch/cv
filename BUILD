load("@bazel_latex//:latex.bzl", "latex_document")

latex_document(
    name = "cv",
    srcs = [
        "cv.tex",
        "profile.jpg",
        "@bazel_latex//packages:geometry",
        "@bazel_latex//packages:moderncv",
    ],
    main = "cv.tex",
)
