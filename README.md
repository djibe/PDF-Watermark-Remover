# PDF Watermark Remover

Remove PDF watermarks from academic papers using [pypdf](https://github.com/py-pdf/pypdf). It is not guaranteed to work, but in most of cases, it just works!

## Setup

Install the pypdf package:

```bash
pip3 install pypdf
```

Or [install UV](https://docs.astral.sh/uv/getting-started/installation/). No `.venv` or `pip install` needed.

## Usage

```bash
python3 remove.py input.pdf output.pdf
```

With UV
```bash
uv run remove.py input.pdf output.pdf
```

## Licence

The code is licensed under the MIT Licence.
