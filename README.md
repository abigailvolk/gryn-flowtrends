# gryn-flowtrends

This repo contains an R Markdown with a compilation of visuals for assessing trends in discharge at publicly available USGS streamgages.

Several things are required by the user before it can be used:

1.  You must specify the Site, Gage number, Start/end dates, and name in the `streamgages` tibble, in Section 1.3.
2.  You must designate the site using the site abbreviation in Section 1.1. `site <- "LMR"`
3.  This script uses the packages: `'dataRetrieval', 'EGRET', 'quantreg', 'tidyverse', 'rkt', 'zyp', 'lubridate', 'kableExtra', 'scales'`. It will ask if you want to install these upon running if they are not installed.

## Please see "example.md" for an example of the output created!

**The script was developed using several references, listed here:**

1.  Cade, B.S. and Noon, B.R., 2003. A gentle introduction to quantile regression for ecologists. *Frontiers in Ecology and the Environment*, *1*(8), pp.412-420.

2.  Gannon, J.P, 9-Flow-Duration-Curves, 2021, Github repository, <https://github.com/VT-Hydroinformatics/9-Flow-Duration-Curves.git>.

3.  Helsel, D.R., Hirsch, R.M., Ryberg, K.R., Archfield, S.A., and Gilroy, E.J., 2020, Statistical methods in water resources: U.S. Geological Survey Techniques and Methods, book 4, chap. A3, 458 p., <https://doi.org/10.3133/tm4a3>. [Supersedes USGS Techniques of Water-Resources Investigations, book 4, chap. A3, version 1.1.].

4.  Hirsch, R.M., and De Cicco, L.A., 2015, User guide to Exploration and Graphics for RivEr Trends (EGRET) and dataRetrieval---R packages for hydrologic data (version 2.0, February 2015): U.S. Geological Survey Techniques and Methods book 4, chap. A10, 93 p., <http://dx.doi.org/10.3133/tm4A10>.

5.  Hirsch, R.M., 2018 (updated 2023), Daily Streamflow Trend Analysis <https://waterdata.usgs.gov/blog/quantile-kendall/>.

6.  Hirsch, R.M., Moyer, D.L., and Archfield, S.A., 2010, Weighted Regressions on Time, Discharge, and Season (WRTDS), with an application to Chesapeake Bay River inputs: Journal of the American Water Resources Association, v. 46, no. 5, p. 857--880, <http://onlinelibrary.wiley.com/doi/10.1111/j.1752-1688.2010.00482.x/full>.

7.  Searcy, J.K., 1959, Flow-duration curves: Water Supply Paper 1542A, accessed at <http://pubs.er.usgs.gov/publication/wsp1542A>.

**Disclaimer** This script is preliminary or provisional and is subject to revision. The software has not received final approval. No warranty, expressed or implied, is made as to the functionality of the software and related material nor shall the fact of release constitute any such warranty. The software is provided on the condition that no one shall be held liable for any damages resulting from the authorized or unauthorized use of the software.
