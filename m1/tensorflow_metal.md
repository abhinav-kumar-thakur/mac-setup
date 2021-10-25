[Tensorflow plugin](https://developer.apple.com/metal/tensorflow-plugin/)

* Install X-code command line tool: `xcode-select --install`
* Install [miniforge](../miniforge/conda.md)
* Create conda env: `conda create --name venv python=3.8`
* Activate conda env: `conda activate venv`
* Install tensorflow dependencies: `conda install -c apple tensorflow-deps -y`
* Install base tensorflow: `pip install tensorflow-macos`
* Install metal plugin: `pip install tensorflow-metal`
