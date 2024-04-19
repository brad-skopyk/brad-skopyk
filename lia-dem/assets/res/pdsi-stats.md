# Comparing Nearest and Non-Nearest Absolute scPDSI

## Data Dictionary

YEARS: Year range of data included in analysis, inclusive of start and end years.

VALID_SES_ENSEMBLE: SES events have been classified into one of seven groups based upon the date of the first reported record for that site. These classes are 1559, 1599, 1649, 1699, 1749, and 1820. For instance, sites classified as 1559 were reported on or before 1559 C.E. 

VALID_GRID_POINTS: Grid points are valid if they are located within 1.5 decimal degrees of an SES site within the VALID_SES_ENSEMBLE. 

RANGEMEAN: The mean scPDSI for all VALID_GRID_POINTS within the VALID_SES_ENSEMBLE.

COUNT: Count of all VALID_GRID_POINTS, with absolute scPDSI values, expressed as v1/v2, where v1 is calculated with VALID_GRID_POINTS within two degrees of lat/lon, but are not the nearest gridpoint to any SES site; and where v2 is calculated with only the nearest VALID_GRID_POINTS to a SES site.

MEAN: The mean PDSI OF VALID_GRID_POINTS, expressed as v1/v2, where v1 is the calculated mean of the absolute scPDSI for *non-nearest* VALID_GRID_POINTS, and where v2 is the calculated mean of the absolute scPDSI for *nearest* VALID_GRID_POINTS.

MEDIAN: The median value of the array of PDSI OF VALID_GRID_POINTS, expressed as v1/v2, where v1 is the calculated median of the absolute scPDSI for *non-nearest* VALID_GRID_POINTS, and where v2 is the calculated median of the absolute scPDSI for *nearest* VALID_GRID_POINTS.

MIN: The minimum scPDSI of VALID_GRID_POINTS, expressed as v1/v2, where v1 is the minimum value of the absolute scPDSI for *non-nearest* VALID_GRID_POINTS, and where v2 is the minimum value of the absolute scPDSI for *nearest* VALID_GRID_POINTS.

MAX: The maximum scPDSI of VALID_GRID_POINTS, expressed as v1/v2, where v1 is the maximum value of the absolute scPDSI for *non-nearest* VALID_GRID_POINTS, and where v2 is the maximum value of the absolute scPDSI for *nearest* VALID_GRID_POINTS.

## Statistics

YEARS: 1518-1820

- VALID_SES_ENSEMBLE: 1518-1820
- RANGEMEAN: 1.2
- COUNT: 160,590/2,121
- MEAN: 1.19/1.3
- MEDIAN: NA/1.14 - NA/NA
- MIN: 0.0/0.002 - NA/NA
- MAX: 6.8/4.9 - NA/NA

YEARS: 1518-1559

- VALID_SES_ENSEMBLE: 1518-1559
- RANGEMEAN: 1.16
- COUNT: 10186/104
- MEAN: 1.16/1.34
- MEDIAN: 1.05/1.2 - NA/NA
- MIN: 0.001/0.005 - NA/NA
- MAX: 4.5/4.6 - NA/NA

YEARS: 1544-1554

- VALID_SES_ENSEMBLE: 1518-1559
- RANGEMEAN: 1.13
- COUNT: 2442/253
- MEAN: 1.37/1.54
- MEDIAN: 1.3/1.43 - 1.2/1.4
- MIN: 0.001/0.004 - 0.07/0.14
- MAX: 4.5/4.6 - 3.56/3.7

YEARS: 1560-1599

- VALID_SES_ENSEMBLE: 1560-1599
- RANGEMEAN: 1.04
- COUNT: 11,325/155
- MEAN: 1.04/0.97
- MEDIAN: 0.87/0.95 - NA/NA
- MIN: 0/0.009 - NA/NA
- MAX: 5.4/2.66 - NA/NA

YEARS: 1574-1579

- VALID_SES_ENSEMBLE: 1560-1599
- RANGEMEAN: 1.13
- COUNT: 1632/90
- MEAN: 1.05/1.36
- MEDIAN: 0.93/1.36 - 0.99/1.3
- MIN: 0.003/0.024 - 0.243/0.37
- MAX: 3.9/2.76 - 2.96/2.53

YEARS: 1600-1649

- VALID_SES_ENSEMBLE: 1600-1649
- RANGEMEAN: 1.13
- COUNT: 16,211/239
- MEAN: 1.13/1.05
- MEDIAN: 1.0/0.9
- MIN: 0/0.002
- MAX: 6.8/4.2

YEARS: 1604-1616

- VALID_SES_ENSEMBLE: 1600-1649
- RANGEMEAN: 1.13
- COUNT: 2,701/55
- MEAN: 1.16/1.3
- MEDIAN: 0.96/1.08
- MIN: 0/0.034
- MAX: 5.4/4.0

YEARS: 1643-1652

- VALID_SES_ENSEMBLE: 1650-1699
- RANGEMEAN: 1.2
- COUNT: 2,932/48
- MEAN: 1.38/1.36
- MEDIAN: 1.2/1.25
- MIN: 0/0.002
- MAX: 5.1/3.3

YEARS: 1650-1699

- VALID_SES_ENSEMBLE: 1650-1699
- RANGEMEAN: 1.2
- COUNT: 19077/252
- MEAN: 1.18/1.25
- MEDIAN: 1.02/1.0
- MIN: 0/0.003
- MAX: 5.3/4.7

YEARS: 1691-1697

- VALID_SES_ENSEMBLE: 1650-1699
- RANGEMEAN: 1.2
- COUNT: 1,598/82
- MEAN: 1.3/1.7
- MEDIAN: 1.28/1.25
- MIN: 0/0.04
- MAX: 5.3/4.7

YEARS: 1700-1749

- VALID_SES_ENSEMBLE: 1700-1749
- RANGEMEAN: 1.15
- COUNT: 20,915/285
- MEAN: 1.12/1.01
- MEDIAN: 0.95/0.85
- MIN: 0/0.003
- MAX: 4.1/4.1

YEARS: 1729-1733

- VALID_SES_ENSEMBLE: 1700-1749
- RANGEMEAN: 1.15
- COUNT: 763/22
- MEAN: 1.2/1.21
- MEDIAN: 1.1/1.1
- MIN: 0/0.085
- MAX: 3.56/2.7

YEARS: 1750-1820

- VALID_SES_ENSEMBLE: 1750-1820
- RANGEMEAN: 1.3
- COUNT: 34,556/1086
- MEAN: 1.28/1.5
- MEDIAN: 1.09/1.36
- MIN: 0/0.003
- MAX: 6.3/4.9

YEARS: 1785-1796

- VALID_SES_ENSEMBLE: 1750-1820
- RANGEMEAN: 1.3
- COUNT: 4,964/412
- MEAN: 1.6/1.77
- MEDIAN: 1.4/1.56
- MIN: 0/0.006
- MAX: 5.2/4.9
