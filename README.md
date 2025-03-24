# QualMeuIP

QualMeuIP is a simple Python project to retrieve and display your public IP address.

## Usage

The most recommended approach to use qualmeuip is call it with `uv`.

### uv
If you have `uv` installed, you can run it with `uvx`:
```bash
uvx qualmeuip
```
output example:
```text
192.168.123.987
```

`uvx` will create a ephemeral virtual env just to run qualmeuip on the fly. If you don't have `uv` installed, you can install with `pipx`:

```bash
pipx install uv
```

### PyPI

or you can install it on your local python environment from `PyPI:
`
```bash
pip install qualmeuip
```

and run the script to get your public IP address:
```bash
qualmeuip
```

Both methods above will display your public IP address in the terminal.

## PyPI address

https://pypi.org/project/qualmeuip/
