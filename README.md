# Data

The underlying microdata are from the **German Socio-Economic Panel (SOEP), teaching edition v37** and are **not included** in this repository.

The analysis covers survey years **2000–2020**. The original thesis merged several SOEP files by person identifier (`pid`) and survey year (`syear`) and produced an unbalanced panel used for the empirical analysis.

To run the R Markdown file locally, obtain authorized access to the appropriate SOEP teaching data and set the environment variable:

```r
Sys.setenv(SOEP_DATA_PATH = "path/to/soep-teaching-v37")
```

The code expects files such as `ppathl.dta`, `pequiv.dta`, and the `raw/` subfolder to exist inside that directory.
