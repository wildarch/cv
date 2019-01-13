# Curriculum Vitae
This repository contains my CV (or résumé).

# Building
[Bazel](https://bazel.build) is required to render the pdf document:
```
bazel build :cv
```
This will produce the CV as a pdf file under `bazel-bin/cv.pdf`.

# Attributions
This CV is built using:
* The ["ModernCV"](http://www.latextemplates.com/template/moderncv-cv-and-cover-letter) LaTeX template
* Bazel [rules for LaTeX](https://github.com/ProdriveTechnologies/bazel-latex)
