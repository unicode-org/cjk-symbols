# CJK Symbols

*CJK Symbols* is a special-purpose CID-keyed OpenType/CFF (aka OTF) font that includes the glyphs for the following 21 Unicode blocks, and covers 19 of them in their entirety:

* [Spacing Modifier Letters](https://www.unicode.org/charts/PDF/U02B0.pdf) &mdash; only U+02EA and U+02EB
* [Enclosed Alphanumerics](https://unicode.org/charts/PDF/U2460.pdf)
* [Dingbats](https://unicode.org/charts/PDF/U2700.pdf) &mdash; only U+2776 through U+2793
* [Ideographic Description Characters](https://unicode.org/charts/PDF/U2FF0.pdf)
* [CJK Symbols and Punctuation](https://unicode.org/charts/PDF/U3000.pdf)
* [Hiragana](https://unicode.org/charts/PDF/U3040.pdf)
* [Katakana](https://unicode.org/charts/PDF/U30A0.pdf)
* [Bopomofo](https://unicode.org/charts/PDF/U3100.pdf)
* [Hangul Compatibility Jamo](https://unicode.org/charts/PDF/U3130.pdf)
* [Kanbun](https://unicode.org/charts/PDF/U3190.pdf)
* [Bopomofo Extended](https://unicode.org/charts/PDF/U31A0.pdf)
* [CJK Strokes](https://unicode.org/charts/PDF/U31C0.pdf)
* [Katakana Phonetic Extensions](https://unicode.org/charts/PDF/U31F0.pdf)
* [Enclosed CJK Letters and Months](https://unicode.org/charts/PDF/U3200.pdf)
* [CJK Compatibility](https://unicode.org/charts/PDF/U3300.pdf)
* [Vertical Forms](https://unicode.org/charts/PDF/UFE10.pdf)
* [CJK Compatibility Forms](https://unicode.org/charts/PDF/UFE30.pdf)
* [Small Form Variants](https://unicode.org/charts/PDF/UFE50.pdf)
* [Halfwidth and Fullwidth Forms](https://unicode.org/charts/PDF/UFF00.pdf)
* [Enclosed Alphanumeric Supplement](https://unicode.org/charts/PDF/U1F100.pdf)
* [Enclosed Ideographic Supplement](https://unicode.org/charts/PDF/U1F200.pdf)

Also included in this project is a TrueType (aka TTF) version of the font that is necessary for Unicode code chart production. The vast majority of its glyphs are derived from [*Source Han Serif*](https://github.com/adobe-fonts/source-han-serif/), specifically the Regular weight.

The latest pre-built binary version of the font, in both OTF and TTF formats, can be easily downloaded from the [Latest Release](https://github.com/unicode-org/cjk-symbols/releases/latest/).

This font is expected to be used as a replacement code chart font starting from Unicode Version 14.0.

## Building the fonts from source

### Requirements

To build the binary font files from source, you need to have installed the [Adobe Font Development Kit for OpenType](https://github.com/adobe-type-tools/afdko/) (AFDKO) tools. The AFDKO tools are widely used for font development today, and are part of most font editor apps.

### Building the fonts

In this repository, all necessary files are in place for building the CID-keyed OpenType/CFF and TrueType fonts, and the *build.sh* file can simply be executed.

## Getting Involved

Send suggestions for changes to the *CJK Symbols* project by submitting a [new issue](https://github.com/unicode-org/cjk-symbols/issues/new).
