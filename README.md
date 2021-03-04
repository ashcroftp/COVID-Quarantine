[![DOI](https://zenodo.org/badge/298576397.svg)](https://zenodo.org/badge/latestdoi/298576397)

# COVID-Quarantine

**Quantifying the impact of quarantine duration on COVID-19 transmission**<br>
Peter Ashcroft, Sonja Lehtinen, Daniel C Angst, Nicola Low, Sebastian Bonhoeffer<br>
eLife (2021) [10.7554/eLife.63704](https://doi.org/10.7554/eLife.63704)


The manuscript is created by the `quarantine.Rmd` R-markdown file, which contains all code required to generate the data and figures.
Running `knitr` on this file will create a PDF manuscript file.

To generate confidence intervals, it is necessary to perform parameter fitting to serial interval data.
The fitting process is costly, but only has to be run once to generate the parameter and distribution samples.
We include the code and the data from Ferretti et al. (2020): *The timing of COVID-19 transmission.* (medRxiv: https://www.medrxiv.org/content/10.1101/2020.09.04.20188516v1) within the R-markdown file.
The original code is accessible at http://doi.org/10.5281/zenodo.4033022.



<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.
