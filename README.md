<p align="center">
  <img src="fig/logo.svg"  width="600"/>
</p>

<h3 align="center">A novel reinterpretation method for high-energy physics results.</h4>

[![Binder](https://binderhub.ssl-hep.org/badge_logo.svg)](https://binderhub.ssl-hep.org/v2/gh/lorenzennio/redist.pyhep/HEAD)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.12638401.svg)](https://doi.org/10.5281/zenodo.12638401)



## Overview
Experimental High Energy Physics has entered an era of precision measurements. However, measurements of many of the accessible processes assume that the final states' underlying kinematic distribution is the same as the Standard Model prediction. This assumption introduces an implicit model-dependency into the measurement, rendering the reinterpretation of the experimental analysis complicated without reanalysing the underlying data.

We present [a novel reweighting method](https://arxiv.org/abs/2402.08417) in order to perform reinterpretation of particle physics measurements. It makes use of reweighting the Standard Model templates according to kinematic signal distributions of alternative theoretical models, prior to performing the statistical analysis. The generality of this method allows us to perform statistical inference in the space of theoretical parameters, assuming different kinematic distributions, according to a beyond Standard Model prediction.

The implementation - redist - is an extension to the [pyhf](https://pyhf.readthedocs.io/) software. It can easily be interfaced with the [EOS](https://eos.github.io/) software, which allows us to perform flavor physics phenomenology studies. Beyond the [pyhf](https://pyhf.readthedocs.io/) or [HistFactory](https://cds.cern.ch/record/1456844/files/CERN-OPEN-2012-016.pdf) likelihood specification, only minimal information is necessary to make a likelihood model-agnostic and hence easily reinterpretable. We showcase that publishing such likelihoods is crucial for a full exploitation of experimental results.


**Check out the paper [here](https://arxiv.org/pdf/2402.08417.pdf).**

## Run locally

```bash
# Clone the redist repository
git clone git@github.com:lorenzennio/redist.pyhep.git

cd redist.pyhep/

# Install dependencies
pip install -r binder/requirements.txt
```

## Contact

For further inquiries, you can talk to us via [Discord](https://discord.gg/bmaVUQcR4w).
