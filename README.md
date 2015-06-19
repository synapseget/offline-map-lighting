
# tributary-maps

Example script to download map tiles.

This standalone script requires `tributary` which is a data processing and analysis library for Python. 

`tributary` can be found at: `https://github.com/eliquious/tributary`

## Installation steps:

1. Create new `virtualenv` (run `virtualenv env`)
2. Activate virtual env (`source env/bin/activate`)
3. Clone `tributary` library from GitHub
4. Install `tributary` dependencies from inside checkout directory (`pip install -e . -r test-requirements.txt`)
5. Install requests (`pip install requests`)
6. Run downloader from `tributary-maps` directory. (`python scripts/lldl.py`)

Currently, there are no command line options (although it would be trivial to add them). The map URL, central lat/lon and zoom levels are hardcoded.

