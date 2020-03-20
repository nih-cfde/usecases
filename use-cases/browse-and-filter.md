---
layout: default
title: Researcher Browse and Filter
nav_order: 1
parent: Use Cases
has_children: false
---
# Use Case UC0001 Researcher Browse and Filter

**Persona:** [Clinical Researcher](../personas/clinical-researcher).

**Objective:** [Multiple DCC Comparison](../objectives/multi-dcc-comparison)

### Summary

Pam wants to build a table of the summarized metadata and summary statistics
from each RNA-Seq dataset in the Common Fund that relates to Focal Cortical Dysplasia.

Pam logs on to the CFDE interface and searches for brain data, and then filters the results to those studies that used RNASeq. She then searches within these results
for "FCD" or "Dysplasia".
The search results identify two CFDE programs with clinical data related to FCD: Kids First and HubMAP. Using links in the search results, Pam accesses the Program
page for each dataset, and decides which to request access to. She also sends
her final table to her postdoc, Lacey, who will do the actual analysis.


### User Tasks

-   [T0001 Access CFDE interface](#access-cfde-interface)
-   [T0006 Search/filter data sets by phenotypic terms](#searchfilter-data-sets-by-phenotypic-terms)
-   [T0005 Search/filter data by type terms](#searchfilter-data-sets-by-type-terms)
-   [T0004 Search within dataset descriptions](#search-within-dataset-descriptions)
-   [T0010 Visualize a table of all datasets that match query](#visualize-a-table-of-all-datasets-that-match-query)
-   [T0002 Explore Program links](#explore-program-links)
-   [T0003 Export a file of results](#export-a-file-of-results)

### Requirements

#### T0001 Access CFDE interface

-   [R00001 The interface will support GUI web access to end users](../requirements/r00001-the-interface-will-support-gui-web-access-to-end-users.md)


#### T0006 Search/filter data sets by phenotypic terms

-   [R00003 The interface will support the selection of an Uberon term of interest](../requirements/r00003-the-interface-will-support-the-selection-of-an-uberon-term-of-interest.md)
-   [R00004 The C2M2 model will support information relating Uberon terms to CF programs](requirements/r00004-the-c2m2-model-will-support-information-relating-uberon-terms-to-cf-programs.md)
-   [R00005 The catalog will store information relating Uberon terms to CF programs](../requirements/r00005-the-catalog-will-store-information-relating-uberon-terms-to-cf-programs.md)


#### T0005 Search/filter data sets by type terms

-   [R00006 The interface will support the selection of an assay type term of interest](../requirements/r00006-the-interface-will-support-the-selection-of-an-assay-type-term-of-interest.md)
-   [R00007 The C2M2 model will support information relating assay types to CF programs](../requirements/r00007-the-c2m2-model-will-support-information-relating-assay-types-to-cf-programs.md)
-   [R00008 The catalog will store information relating assay types to CF programs](../requirements/r00008-r00008-the-catalog-will-store-information-relating-assay-types-to-cf-programs.md)
-   [R00010 The catalog will store information relating projects to CF programs](../requirements/r00010-the-catalog-will-store-information-relating-projects-to-cf-programs.md)
-   [R00011 The C2M2 model will support information relating projects to CF programs](../requirements/r00011-the-c2m2-model-will-support-information-relating-projects-to-cf-programs.md)


#### T0004 Search within results

-   [R00009 The interface will support free text search of results](../requirements/r00009-the-interface-will-support-free-text-search-of-results.md)

#### T0010 Visualize a table of all projects that match query

-   [R00012 The interface will render tables and plots to display filtered data](../requirements/r00012-the-interface-will-render-tables-and-plots-to-display-filtered-data.md)

#### T0002 Explore Program links

-   [R00013 The interface will support links to original data sources within the results](../requirements/r00013-the-interface-will-support-links-to-original-data-sources-within-the-results.md)

#### T0003 Export a file of results

-   [R000014 The interface will support end user download of tables and figures in common formats](../requirements/r000014-the-interface-will-support-end-user-download-of-tables-and-figures-in-common-formats.md)
