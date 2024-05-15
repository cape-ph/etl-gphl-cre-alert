# etl-gphl-cre-alert

**_TODO_** This README needs work. And we should make sure all our ETL scripts
have the same README format.

Repo containing the Epi/HAI ETL for a GDPH Carbapenem-resistant
Enterobacterales (CRE) alert file uploaded to the raw Epi/HAI data bucket in
CAPE.

The ETL script will extract the tabular data and convert it to a common format
that will then be written into the clean data bucket for later query.

## Raw File Format

This file is given as a `.docx` containing a single table that will be
processed by this ETL script. Should the data expected be in anything
other than the first table in this file the ETL will fail.

### Column Set

**_TODO_** Add description of expected columns

## Cleaned Format

This section describes the common format that will result from this ETL.

### Column Set

**_TODO_** Add description of expected columns

## Failure Modes

**_TODO_** Add description of ways this script can fail (e.g. no table of
expected raw data, table in wrong location, missing columns, etc.). This will
require better error handling be added to the script.
