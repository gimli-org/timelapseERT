# timelapseERT
Timelapse ERT data and notebooks based on pyGIMLi

This repository is targeted at timelapse (monitoring) Electrical Resistivity Tomography (ERT).
It holds data sets that can be freely used by researchers, but also bears notebooks demonstrating
how to do the data analysis so that the published results can be reproduced by simple scripts.

All methods are contained in the pyGIMLi (Rücker et al. 2017) software. The ERT module holds
classes for convenient and automated data import, visualization, inversion and export.
The whole workflow is illustrated by simple Jupyter notebooks, while the magic is mainly in
the underlying classes for ERT inversion, timelapse processing, mesh generation etc.

We collected a few cases that are all freely available and well-documented (and citable):

|Name        |Reference            |dim  |time|data |Info               |
|------------|---------------------|---  |---:|----:|-------------------|
|pyGIMLi     |Rücker et al. (2017) |2D   |  10|  740|synth. tracer exp. |
|Hillslope   |Hübner et al. (2015) |2D   |  24|  800|min. length        |
|ALERT       |Kuras et al. (2009)  |2D xh|  35| 1200|9 boreholes        |
|Infiltration|Hübner et al. (2017) |3D   | 200| 2850|min. length        |
|Tsunami     |Ronczka et al. (2014)|2.5D | 900|  225|                   |
|Steelcase   |Ronczka et al. (2015)|3D SC|   9|  450|SEM model, regions |
|SAMOS       |Ronczka et al. (2020)|3D/2D|   7| 3000|CEM model          |
|TestUM      |Birnstengel et al. ()|3D xh|  70| 2200|                   |
|DynaDeep    |Skibbe et al. ()     |2D   |  10| 3000|changing topography|


## References
* Kuras, O., Pritchard, J., Meldrum, P. I., Chambers, J. E., Wilkinson, P. B., Ogilvy, R. D., and Wealthall, G. P. (2009). Monitoring hydraulic processes with Automated time-Lapse Electrical Resistivity Tomography (ALERT). Compte Rendus Geosciences - Special issue on Hydrogeophysics, 341(10-11):868–885.
* Ronczka, M., Günther, T. & Stoeckl, L. (2014): Geoelectrical monitoring of freshwater-saltwater interaction in physical model experiments. Ext. Abstr. 23rd Saltwater Intrusion Meeting, Husum, Germany.
* Hübner, R., Heller, K., Günther, T. & Kleber, A. (2015): Monitoring hillslope moisture dynamics with surface ERT for enhancing spatial significance of hydrometric point measurements. Hydrology and Earth System Sciences 19(1), 225-240, doi:10.5194/hess-19-225-2015.
* Persson, M., Dahlin, T. & Günther, T. (2015): Observing solute transport in the capillary fringe using image analysis and electrical resistivity tomography in laboratory experiments. Vadose Zone Journal 14(5), 11p, doi:10.2136/vzj2014.07.0085.
* Ronczka, M., Voss, T. & Günther, T. (2015): Cost-efficient imaging and monitoring of saltwater in a shallow aquifer by using long-electrode ERT. J. of Appl. Geoph. 122, 202-209, doi:10.1016/j.jappgeo.2015.08.014.
* Rücker, C., Günther, T., Wagner, F.M. (2017): pyGIMLi: An open-source library for modelling and inversion in geophysics, Computers & Geosciences 109, 106-123, doi:10.1016/j.cageo.2017.07.011.
* Hübner, R., Günther, T., Heller, K., Noell, U. & Kleber, A. (2017): Impacts of a capillary barrier on infiltration and subsurface stormflow in layered slope deposits monitored with 3-D ERT and hydrometric measurements. Hydrol. Earth Syst. Sci. 21, 5181-5199, doi:10.5194/hess-21-5181-2017.
* Birnstengel et al. (in prep.)
* Skibbe et al. (in prep.)
