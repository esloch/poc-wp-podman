# poc-wp-podman

Requirements:

mamba env create -f conda/dev.yaml

``` 
# Run:
curl -sSL https://raw.githubusercontent.com/pdm-project/pdm/main/install-pdm.py | python3 -
``` 
pdm config venv.backend conda


for add new packages use:
pdm add -dG dev ipython
pdm add -dG linting isort black flake8
