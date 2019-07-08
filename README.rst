SouthernOcean-ARGO
==================

.. image:: https://mybinder.org/badge_logo.svg
    :target: https://mybinder.org/v2/gh/roxyboy/SouthernOcean-ARGO/master

This repository contains the analysis scripts used for the paper *Characterizing the Seasonality of Phytoplankton Biomass in the Southern Ocean Observed by Biogeochemical Floats*. Uchida. T., D. Balwada, R. Abernathey, P. Channing, E. Boss, and S. Gille. (2019) JGR: Oceans (`DOI`_). 
We provide the notebooks for quality control using a `SOCCOM float 5904185 <SOCCOM/5904185.ipynb>`_ as a representative, `phytoplankton biomass over the whole dataset <Cphyto.ipynb>`_, and the timing of each spring bloom phase, viz. `onset, climax and apex <COMCLIMphasing.ipynb>`_. 

All notebooks in this repository are openable on `Binder`_ but data is only provided for `SOCCOM/5904185.ipynb <SOCCOM/5904185.ipynb>`_.
You can set load an arbitrary float by downloading the dataset via `wget <https://www.computerhope.com/unix/wget.htm>`_ in the notebook (Starting up Binder can take some time depending on the server condition, please be patient).

The biogeochemical floats used in our study are operated by the SOCCOM and SOCLIM projects and data collected are available publicly by the International Argo Program and national programs tha contribute to it (http://www.argo.ucsd.edu, http://argo.jcommops.org). The data used in our paper were downloaded from the `SIO`_ and `SOCLIM`_ portal respectively.

.. _DOI: 
.. _Binder: https://mybinder.org/v2/gh/roxyboy/SouthernOcean-ARGO/master
.. _SIO: http://soccom.ucsd.edu/floats/SOCCOM_data_ref.html
.. _SOCLIM: http://www.obs-vlfr.fr/proof/php/SOCLIM/soclim_float.php

