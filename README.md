# pagebrew-v2

My tiny static site generator, ~100 lines of Python

Side project, maintained when I have time.

## Highlights

- Single template, plain str.format, no Jinja
- Markdown posts with fenced code and tables
- Index page with post list by date
- RSS feed generation

## Usage

```bash
mkdir posts && echo '# hello' > posts/first.md
python build.py
# site lands in dist/
```

## Installation

```bash
pip install -r requirements.txt
```

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── configuration.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
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
