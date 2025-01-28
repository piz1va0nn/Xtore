# Xtore

Xtore: A simple storage module with simple indexing.

## Setup

### Install the base library, used for create Virtual Environment
```bash
sudo apt-get install < requirements-ubuntu.txt
```

### Create Virtual Environment, Activate, and Install required library
```bash
mkdir venv
python -m venv ./venv/
source venv/bin/activate
pip install -r requirements.txt
```

### Build, Cythonizing, and Link Project
```bash
python setup.py build
python XtoreSetup.py link
```

## (Optional) Use .devcontainer
- Open docker daemon (or just open docker desktop)
- On remote window options, `Reopen in Container`
- Activate the virtual environment (default as [/venv](/venv))

## Create Command
- Create command line class at [/src/xtore/cli](/src/xtore/cli)
- Create command script at [/script](/script/)
- Run link command `python XtoreSetup.py link`
- Change access permission script file with `chmod +x /script/{script name}`
- Try run script on terminal 👩‍💻
