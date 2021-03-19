# Zeth-related simulations and models

This notebook models various Zeth instantiations under different blockchain configurations and aims to study the blockchain state growth over time.

:turtle: **WARNING** the simulations in this notebook can take a significant amount of time. Please be sure to adjust the number of simulation timesteps if you wish to run the simulation on a smaller timeframe for faster results.

*Note:* This notebook can also be used to model "plain" chain state growth (if only "EoA-to-EoA" transactions are done) by commenting out the relevant pieces of the notebook. It can also be extended and adjusted to model the impact of different L2 solutions on the system's state growth.

## Citations

If you wish to cite this notebook, you may use the following:

```
@misc{zeth-state-simulation2021,
    author={Antoine Rondelet},
    title={Zeth cadCAD Simulations},
    howpublished={\url{https://github.com/clearmatics/simodelation/blob/master/zeth/zeth-cadCAD-simulation.ipynb}},
    year={2021}
}
```

Be aware that the content of the notebook may be changed in subsequent commits. Hence it is worth adding a `note` entry to the citation block above to refer to the access date and the git commit at which the notebook was accessed.
