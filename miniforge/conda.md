# [Miniforge](https://github.com/conda-forge/miniforge) MAC m1

## Install Miniforge
* Download and run Apple Silicon installation script from [here](https://github.com/conda-forge/miniforge)
* Disable default base `conda config --set auto_activate_base false`

## Remove conda / miniforge
* Remove the root prefix
`rm -rf $(conda info --base)`
* Configuration file, common between conda installations
`rm ~/.condarc`
* Environment locations and system information
`rm -rf ~/.conda`
* Clean anything in shell initialization files