# Clozure CL macOS builder
This is a GitHub workflow that builds a macOS .app for [Clozure CL](https://github.com/Clozure/ccl)
(CCL for short) LISP IDE using GitHub runners.

Unfortunately, the upstream project does not provide macOS IDE binaries, so this project is here to
address that. While there is an
[older version of CCL on the Apple App Store](https://apps.apple.com/ca/app/clozure-cl/id489900618?mt=12),
it doesn't seem to work well with latest releases of macOS. Also, that version has not been updated
by the author since 2019.
