# Project Motivation

This is analysis for a blog project required in Udacity Data Scientist Nanodegree. It uses several datasets to analyze with respect to the global temperature anomaly.

[Link to Medium Post](https://medium.com/@ambreen2006/when-we-try-to-pick-out-anything-by-itself-we-find-it-hitched-to-everything-else-in-the-universe-4b0cefb8603c)
<br/><br/>
CRISP-DM process followed is documented below

## Dataset

* Various datasets are obtained and sources are documented in the reference section.
* Each variable used is explained and analyzed in the notebook `Global Temperature Trend.ipynb`

## Data preparation

* NaN values are removed where applicable
* Data is standardized using standard scaler

## Analysis and Modeling

* The output variable's timeline is visualized seperately as well as with explanatory variables
* LinearRegression model is created using `scikit` to infer coefficients
* Different correlation methods with p-values are considered to understand the variables.

## Summary of the Results

* Linear regression model for the global temperature trend was created.
* The average rate of increase in global temperature per decade after 1981 is much higher then what it is since 1880 per decade.
* Greenhouse gases play a significant role in the increasing temperature.
* Stratospheric aerosols cools the temperature.
* A multivariable regression model was created and evaluated.

## Resources and DataSets Sources:

[1] Herring, S. C., N. Christidis, A. Hoell, M. P. Hoerling, and P. A. Stott, Eds., 2020: Explaining Extreme Events of 2018 from a
Climate Perspective. Bull. Amer. Meteor. Soc., 101 (1), S1–S128, doi:10.1175/BAMS-ExplainingExtremeEvents2018.1.
[2] Herring, S. C., A. Hoell, M. P. Hoerling, J. P. Kossin, C. J. Schreck III, and P. A. Stott, Eds., 2016: Explaining Extreme Events of
2015 from a Climate Perspective. Bull. Amer. Meteor. Soc., 97 (12), S1–S145.
[3] GISTEMP
GISTEMP Team, 2020: GISS Surface Temperature Analysis (GISTEMP), version 4. NASA Goddard Institute for Space Studies. Dataset accessed 20YY-MM-DD at https://data.giss.nasa.gov/gistemp/.
Lenssen, N., G. Schmidt, J. Hansen, M. Menne, A. Persin, R. Ruedy, and D. Zyss, 2019: Improvements in the GISTEMP uncertainty model. J. Geophys. Res. Atmos., 124, no. 12, 6307–6326, doi:10.1029/2018JD029522.
[4] AGGI
https://www.esrl.noaa.gov/gmd/aggi/aggi.html)
Graphic: The Greenhouse Effect https://climate.nasa.gov/climate_resources/188/graphic-the-greenhouse-effect/
Greenhouse effect https://courses.edx.org/assets/courseware/v1/f40bce9bb2f3570cc65b5303558ab895/asset-v1:SDGAcademyX+CCSI001+3T2019+type@asset+block/Module_1_Reading_5.pdf
[5] TSI
ftp://ftp.pmodwrc.ch/pub/data/irradiance/composite/
https://www.pmodwrc.ch/en/home/[6] Interpreting Correlations
[6] Interpreting correlations
https://towardsdatascience.com/eveything-you-need-to-know-about-interpreting-correlations-2c485841c0b8
[7] ENSO
Graphics https://en.wikipedia.org/wiki/El_Ni%C3%B1o#/media/File:ENSO_-_normal.svg
Graphics https://en.wikipedia.org/wiki/El_Ni%C3%B1o#/media/File:ENSO_-_El_Ni%C3%B1o.svg
https://www.nationalgeographic.org/encyclopedia/el-nino/
https://www.nationalgeographic.org/encyclopedia/la-nina/
https://psl.noaa.gov/cgi-bin/data/climateindices/corr.pl?tstype1=27&custname1=&custtitle1=&tstype2=0&custname2=&custtitle2=&year1=&year2=&itypea=0&y1=&y2=&plotstyle=0&length=&lag=&iall=0&iseas=1&mon1=0&mon2=11&anom=1&climo1_yr1=&climo1_yr2=&climo2_yr1=&climo2_yr2=&Submit=Calculate+Results
https://www.climate.gov/news-features/understanding-climate/el-ni%C3%B1o-and-la-ni%C3%B1a-frequently-asked-questions
http://faculty.washington.edu/kessler/occasionally-asked-questions.html#q1
https://www.youtube.com/watch?v=dzat16LMtQk
https://psl.noaa.gov/enso/mei/
