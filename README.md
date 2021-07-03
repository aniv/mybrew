# MyBrew

Generates a current listing of locally installed [Homebrew](https://brew.sh/) apps

## Usage

Run `python3 brew.py` and review pull requests on Github.com periodically for changes

To install `brew` packages from the list generated, run `xargs brew install < apps.txt`

## Configuration

1. Setup Python environment: `pip install -r requirements.txt`
2. Edit `config.py` with correct values (see sample)