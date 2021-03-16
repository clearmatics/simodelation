# Simodelation: Clearmatics Research Simulations and Models

```console
$ echo $(sed "s/mul/model/g" <<<$(echo "Simulation"))
$ Simodelation
```

This repository contains some open-sourced models and simulation results carried out along the design and instantiation of various protocols.

## Dependencies

- Python (version `>= 3.7`)

```console
python3.7 -m venv env
source env/bin/activate
pip install --upgrade pip
pip install cadCAD jupyter numpy tabulate pandas plotly
```

To start a notebook, run:
```console
jupyter notebook <notebook-name>
```

E.g.
```console
jupyter notebook zeth/zeth-cadCAD-simulation.ipynb
```

**Note:** It is also possible to simply install the [Anaconda Python distribution](https://docs.anaconda.com/anaconda/install/) which comes with most of the necessary python packages.

This repository uses cadCAD for modelling and simulations, see [here](https://github.com/cadCAD-org/) for introductory materials.
