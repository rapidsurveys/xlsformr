
<!-- README.md is generated from README.Rmd. Please edit that file -->

# xlsformr: Creating XLSForms for Open Data Kit Using R

[![Project Status: WIP – Initial development is in progress, but there
has not yet been a stable, usable release suitable for the
public.](https://www.repostatus.org/badges/latest/wip.svg)](https://www.repostatus.org/#wip)
[![lifecycle](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)

Open Data Kit (ODK) uses a low-level form specification based on XForms.
However, XForms can still prove challenging to use for creating forms.
XLSForm, a high-level Excel-based\[1\] form specification, has been
developed to facilitate creation of ODK forms for majority of users as
it uses a tool that is familiar with most.

XLSForm is a form standard created to help simplify the authoring of
forms in Excel. Authoring is done in a human readable format using a
familiar tool that almost everyone knows - Excel. XLSForms provide a
practical standard for sharing and collaborating on authoring forms.
They are simple to get started with but allow for the authoring of
complex forms by someone familiar with the syntax described below.

The XLSForm is then converted to an XForm, a popular open form standard,
that allows you to author a form with complex functionality like skip
logic in a consistent way across a number of web and mobile data
collection platforms. XLSForms are compatible with the subset of XForm
functionality supported by Javarosa Project. XLSForms are supported by a
number of popular data collection platforms.

This package provides functions to create an XLSForm using R.

## Installation

`xlsformr` is not yet available on CRAN. `xlsformr` can be installed via
GitHub as follows:

``` r
if(!require(devtools)) install.packages("devtools")
devtools::install_github("rapidsurveys/xlsformr")
```

<br/> <br/>

1.  Other spreadsheet applications that behave similar to Excel, such as
    Open Data Format Spreadsheets (ODS) and Google Sheets, are also
    compatible.
