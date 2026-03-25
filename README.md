## ⚠️ No longer maintained.

This script is **no longer maintained** and will not receive any further updates or bug fixes.

### Replacement

Please use [`fzp_checker.py`](https://github.com/fritzing/fritzing-parts/blob/main/fzp_checker.py) from the [fritzing-parts](https://github.com/fritzing/fritzing-parts) repository instead.

A quick start for the replacement is

```sh
cd fritzing-parts
uv run --with-requirements scripts/checks/requirements.txt fzp_checker.py --help
```

## Description

FritzingCheckPart.py is a python script that checks parts files for use by
the Fritzing EDA program (fritzing.org). It started to correct some of the
issues that Fritzing has with the output from the Inkscape (inkscape.org)
open-source SVG editor program. It then grew into checking the format of
the various file (FZP and SVG) that make up a fritzing part. As a part of
that, it also prettyprints XML (with varying success). It does best with
post-processed fritzing SVG files because it understands their format and
has modified the XML (mostly moving CSS style commands into inline XML,
which as a side effect makes prettyprinting easier) to better suit
fritzing. A standalone script, PP.py, is included, which will pretty-print
an XML document without any fritzing-related conversions.

## Installation

Removed. See EOL message above.

