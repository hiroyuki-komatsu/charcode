# charcode
Web tool to edit characters based on Unicode code points.

[Demo: hiroyuki-komatsu.github.io/charcode](https://hiroyuki-komatsu.github.io/charcode/index.html)

Features
* Conversion from an encoding to other encoding.
  + e.g. abc (plan text) → %61%62%63 (UTF8 %NN)
* Modification per code point with drag and drop.

Supported encodings
* plain text
* UTF32 &#xNNNN;
* UTF32 \u{NNNN}
* UTF16 \uNNNN
* UTF8 \xNN
* UTF8 %NN
