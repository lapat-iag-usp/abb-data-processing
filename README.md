# ABB Data Processing

The goal of [this script](data-processing.ipynb) is to preprocess the data from LGR-ICOS<sup>TM</sup> Microportable Gas Analyzer. The preprocessed data is displayed on the [Metroclima dashboard](http://www.metroclima.iag.usp.br/dashboard/) (login is required).

The script that plots the data on the dashboard can de found [here](https://github.com/lapat-iag-usp/metroclima-masp/blob/1c115724a6fa5847a2a06d185297776de1fbcb21/metroclima/dashboard/views.py#L211).

The [script](data-processing.ipynb):
- unzip the files
- remove the first line
- remove the message at the end of the file
- remove white spaces
