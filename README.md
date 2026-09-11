# quillstatic

Static blog generator: markdown in, tidy HTML out

Small but I use it weekly.

## Installation

```bash
pip install -r requirements.txt
```

## How to use

```bash
mkdir posts && echo '# hello' > posts/first.md
python build.py
# site lands in dist/
```

## What it does

- Markdown posts with fenced code and tables
- Index page with post list by date
- Single template, plain str.format, no Jinja
- RSS feed generation

## Project structure

```text
├── docs/
│   ├── development.md
│   ├── faq.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── build.py
└── requirements.txt
```

## Development

```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
```

## License

MIT - see [LICENSE](LICENSE).
