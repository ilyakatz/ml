## Prerequisites

```
pip3 install virtualenv
virtualenv ml
source ml/bin/activate
pip3 install jupyter matplotlib pandas numpy scipy sklearn bokeh jupyter_contrib_nbextensions jupyter_nbextensions_configurator matplotlib

jupyter contrib nbextension install --user
jupyter nbextensions_configurator enable --user
```

## Start the notebook

```
cd ml
source bin/activate
jupyter notebook
```
