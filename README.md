[![CI](https://github.com/HinTak/webkitgtk-mod-CI/actions/workflows/ci.yml/badge.svg)](https://github.com/HinTak/webkitgtk-mod-CI/actions/workflows/ci.yml)

This repo is an experiment trying to addess:
[[GTK] regression: ot-svg font support lost in 2.46 with skia](https://bugs.webkit.org/show_bug.cgi?id=283246).
[Fixed commit](https://commits.webkit.org/287859@main).
[Direct link to fixed commit](https://github.com/WebKit/WebKit/commit/7bf0c3997b61bfa7e3410d5452fd23d82b7570ab).
The fix is first available in `webkitgtk-2.47.3`.

[REGRESSION(287859@main): Building with USE_SKIA_OPENTYPE_SVG=ON fails with Clang 18.1+](https://bugs.webkit.org/show_bug.cgi?id=284779)

[Building in C++23 mode with Clang fails on SkDOM.cpp](https://issues.skia.org/384605093)

Go to either of the two urls (the bottom half of the latter) to see the difference:
https://pixelambacht.nl/chromacheck/
https://yoksel.github.io/color-fonts-demo/


COLRv1:
[30 Mar 2021](https://lists.webkit.org/pipermail/webkit-dev/2021-March/031765.html)
[20 Apr 2021](https://lists.webkit.org/pipermail/webkit-dev/2021-April/031789.html)
[3 May 2021](https://lists.webkit.org/pipermail/webkit-dev/2021-May/031839.html)

OT-SVG:
[11 Sep 2014](https://lists.webkit.org/pipermail/webkit-dev/2014-September/026848.html)
