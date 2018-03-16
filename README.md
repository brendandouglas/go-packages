# Dummy project with Go packages spread across multiple directories

## Setup instructions in IntelliJ:

  * Download Bazel
  * Install the Bazel IntelliJ plugin
  * 'File > Import Bazel Project...', select new Bazel workspace with repo root directory
  * Select 'Import project view file', and choose 'go-packages/.bazelproject'
  * Launch 'Bazel run reference:main' run configuration, auto-created at startup