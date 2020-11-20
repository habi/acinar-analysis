[![DOI](https://zenodo.org/badge/140433592.svg)](https://zenodo.org/badge/latestdoi/140433592)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/habi/acinar-analysis/master)
[![Join the chat at https://gitter.im/habi/Lungs](https://badges.gitter.im/habi/Lungs.svg)](https://gitter.im/habi/Lungs)

This repository contains all the analysis we had to do to be able to write the manuscript on the *Pulmonary acini exhibit complex changes during postnatal rat lung development*.
A preprint of the manuscript can be found on bioRxiv with the DOI [10.1101/786681](https://doi.org/10.1101/786681).
The manuscript was submitted to the [American Journal of Physiology- Lung Cellular and Molecular Physiology](https://journals.physiology.org/journal/ajplung).

The main calculations are done in [this Jupyter notebook](Analysis.ipynb) (a copy of which you can run in [Binder](https://mybinder.org/) by clicking on the second badge above).
Said notebook also generates most of the figures (in Python it would be `figures[1:]`), which have been copied as PNG images to [the Authorea document](https://www.authorea.com/274247/47HwqAxume3L2xkLOsg_SQ) which we've edited collaboratively between all Co-Authors.
Since Figure 1 was a bit more complicated, we generated it from the raw data with [its own Jupyter notebook](https://github.com/habi/acinar-analysis/blob/master/MicroscopyFigure.ipynb).

The other [Jupyter notebooks](http://jupyter.org) and XLS sheets in this repository have been used for detail work in the manuscript or to quickly grasp what's in the raw data.
The [file `acinidavid.pzf`](https://github.com/habi/acinar-analysis/blob/master/acinidavid.pzf) is a file which Tiziana used for a preliminary analyis of the data in [Prism](https://www.graphpad.com/scientific-software/prism/).

The delineated datasets of the +700 acini that we used for the analyis can be provided on request (since they're too big/distrubuted to be shared directly online).
A copy of the data extracted from these datasets is added to the repository as `Datafile_$githash.pkl`, so you technically don't need it to follow along with our results.
This should enable you to get exactly the same results as we did, e.g. do some [reproducible research](https://en.wikipedia.org/wiki/Reproducibility#Reproducible_research).

Please get in touch with me if youd like to try, I'm happy to help!
You can either send me an [email](https://www.anatomie.unibe.ch/haberthu), [file an issue](https://github.com/habi/Zebra-Fish-Gills/issues) or use the 'chat on Gitter' badge on top to start a chat.
