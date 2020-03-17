---
layout: default
title: NIH Compare across DCCs
nav_order: 2
parent: Use Cases
has_children: false
---

# Use Case 002 Explore data availability to build policy

**Persona:** [Program Officer](../personas/program-officer).

**Objective:** [Multiple DCC Comparison](../objectives/multi-dcc-comparison)

### Summary

Jon is a leader at the Common Fund, and wants to build summary tables of
Common Fund assets for use in both tracking progress and for finding gaps that
should be filled by future initiatives. They would like to use the CFDE dashboard
to download simple tables or graphs that show what assets exist, and where.

Using a web browser, Jon uses a point and click interface to get a matrix of
Uberon tissue terms by DCC. With a few more clicks, they gets similar tables showing
Species, and Experiment Types by Program.

Since these are simple binary matrices, Jon can plot the data in almost any
piece of plotting software. Since they would like to see what terms are most broadly
and most infrequently found in the Common Fund, they opts for using UpSet, which
will automatically render her data in a type of multidimensional venn diagram.

### User Tasks

-   [Access to CFDE portal](#access-cfde-portal)
-   [Search/filter CF Programs by phenotypic terms](#searchfilter-common-fund-programs-by-phenotypic-terms)
-   [Search/filter CF Programs by data type terms](#search-filter-common-fund-programs-by-data-type terms)
-   [Visualize a table of all datasets that match query](#visualize-a-table-of-all-datasets-that-match-query)
-   [Export a file of results](#export-a-file-of-results)

### Requirements

#### Access CFDE portal

-   The portal will support GUI web access to end users
-   The portal will support user authentication

#### Search/filter Common Fund Programs by phenotypic terms

-   The portal shall support the selection of an anatomical term of interest.

#### Search/filter Common Fund Programs by data type terms

-   The C2M2 model shall support information relating datatypes to CF programs
-   The catalog shall store information relating datatypes to CF programs

#### Visualize a table of all datasets that match query

-   The catalog shall store information relating datasets to CF programs
-   The C2M2 model shall support information relating datasets to CF programs
-   The portal will render tables to display filtered data


#### Export a file of results

-   The portal shall support end user download of tables and figures in common formats
