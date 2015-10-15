# cluefs tools - lsst-demo-v10.1

This directory contains a Python notebook for exploring the contents of the data collected and emitted by [clueFS](https://github.com/airnandez/cluefs) while executing the demonstration software of the [LSST](http://dm.lsst.org/) software framework v11.0.

In addition to the Python code, this repository contains the trace data in CSV format so that you can explore by yourself. The included trace data was collected when running the demo in a physical machine running CentOS 7. The input and output data needed for running the demo were located on a local file system. The format of each CSV record is [documented here](https://github.com/airnandez/cluefs/blob/master/doc/EventFormats.md).

## How to use

In order to use this notebook, you need Python v3.4 installed on your computer and a few additional packages the notebook depends on. You may consider [Anaconda Python v3.4](http://continuum.io/downloads#py34) which contains all the components needed by this notebook.

To run the notebook clone this repository and launch iPython:

```bash
$ git clone https://github.com/airnandez/cluefs-tools
$ cd cluefs-tools/lsst-demo-v11.0
$ ipython notebook
```

## Cannot view the notebook's graphics?

If you experience some problems viewing the notebook's graphics on Github, you may want to view it via [nbviewer.ipython.org](http://nbviewer.ipython.org/github/airnandez/cluefs-tools/blob/master/lsst-demo-v11.0/lsst-demo-v11.0.ipynb).

## How to contribute

If you experience some issues using this tool, please don't hesitate to [open an issue](https://github.com/airnandez/cluefs-tools/issues).


