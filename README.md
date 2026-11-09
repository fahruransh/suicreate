# suicreate

Auto-create Sui wallets in bulk.

> ⚠️ Note: the current `sui.py` is shipped as an obfuscated/minified blob, so its exact
> behaviour could not be verified by reading the code. Review it (or replace it with a
> readable implementation) before running it.

## Requirements

- Python 3

## Setup

```bash
pip install -r requirements.txt
```

## Usage

```bash
python sui.py
```

## Tech

- Python
- `pynacl` (Sui key generation)
