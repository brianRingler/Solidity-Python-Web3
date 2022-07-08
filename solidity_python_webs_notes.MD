# Solidity-Python-Web3 Project

## pip install web3
  * All required ETH packets installed with web3
  * jsonschema-4.6.2 (Need 3.2.0) '''pip install --force-reinstall jsonschema==3.2.0
  * typing-extensions-4.3.0

## pip install eth-tester
  * Encountered error while trying to install package -> `cytoolz`
  * python -m pip uninstall cytoolz - Gave me a warning that cytoolz is not installed
  * Installed `Cython-0.29.30` - `cytoolz` should be installed with `Cython`
  
-- Will this fix the `legacy-install-failure`
  * python -m pip install --upgrade pip
  * pip install --upgrade wheel
  * pip install --upgrade setuptools
  * pip install python-dev-tools

## Working with pipenv 
* For Error: --system is intended to be used for pre-existing Pipfile installation, 
* use `pipenv --ven` to locate duplicate folder and just remove that one