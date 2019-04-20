
<!-- README.md is generated from README.Rmd. Please edit that file -->

# xlsformr: Creating XLSForms for Open Data Kit Using R

Open Data Kit (ODK) uses a low-level form specification based on XForms.
However, XForms can still prove challenging to use for creating forms.
XLSForm, a high-level spreadsheet-based form specification, has been
developed to facilitate creation of ODK forms for majority of users as
it uses a tool that is familiar with most.

XLSForm is a form standard created to help simplify the authoring of
forms in a spreadsheet. Authoring is done in a human readable format
using a familiar tool that almost everyone knows - spreadsheet tools
such as Excel. XLSForms provide a practical standard for sharing and
collaborating on authoring forms. They are simple to get started with
but allow for the authoring of complex forms by someone familiar with
the syntax described below.

The XLSForm is then converted to an XForm, a popular open form standard,
that allows you to author a form with complex functionality like skip
logic in a consistent way across a number of web and mobile data
collection platforms. XLSForms are compatible with the subset of XForm
functionality supported by Javarosa Project. XLSForms are supported by a
number of popular data collection platforms.

This package provides functions to create an XLSForm using R.
