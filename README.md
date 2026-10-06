# VectorDriftCheck

Compare embedding snapshots and report cosine-similarity, vector-norm, missing-ID, and representation drift across model or pipeline changes.

Version: **1.0.0**

## Installation

```bash
git clone https://github.com/bafnayeygian/VectorDriftCheck.git
cd VectorDriftCheck
python -m pip install .
```

## Usage

```bash
vector-drift-check --help
```

## Development

```bash
python -m unittest discover -s tests -v
python -m compileall -q src
```

## License

MIT License.
