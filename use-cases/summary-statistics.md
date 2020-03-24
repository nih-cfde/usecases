---
layout: default
title: Summary Statistics
nav_order: 3
parent: Use Cases
has_children: true
---
# Use Case UC0003 Monitor Data Releases as a Data Custodian

**Persona:** [Data Custodian](../personas/data-custodian).

**Objective:** [Monitor Data Releases](../objectives/single-dcc-release)

# Summary

Janice is the PI for data coordinating center. She would like
to use the CFDE interface to help write a progress report for her funding agency.
Using the browse and filter functions on the CFDE interface she creates a report
containing relevant summary statistics for datasets owned by her DCC, and
rendered graphs and figures of the summary data. This includes information such
as how much data is currently publicly available on her DCC portal, how much is
uploaded but embargoed, the FAIRness score for these datasets, and how these
statistics have changed over the previous year.

### User Tasks

-   [T0001 Access to CFDE interface](#access-cfde-interface)
-   [T0007 Summarize all datatypes hosted by CF Program X](#summarize-all-datatypes-hosted-by-cf-program-x)
-   [T0009 Summarize FAIRness scores by CF Program X](#summarize-fairness-scores-by-cf-program-x)
-   [T0008 Summarize FAIRness scores by CF Program X over time](#summarize-fairness-scores-by-cf-program-x-over-time)
-   [T0010 Visualize a table of all datasets that match query](#visualize-a-table-of-all-datasets-that-match-query)
-   [T0003 Export a file of results](#export-a-file-of-results)

### Requirements

#### T0001 Access CFDE interface

-   [R00001 The interface will support GUI web access to end users](../requirements/r00001-the-interface-will-support-gui-web-access-to-end-users.md)
-   [R00002 The interface will support user authentication](../requirements/r00002-the-interface-will-support-user-authentication.md)

#### T0007 Summarize all assay types hosted by CF Program X

-   [R00018 The interface will support the selection of a CF Program of interest](../requirements/r00018-the-interface-will-support-the-selection-of-a-cf-program-of-interest.md)
-   [R00007 The C2M2 model will support information relating assay types to CF programs](../requirements/r00007-the-c2m2-model-will-support-information-relating-assay-types-to-cf-programs.md)
-   [R00008 The catalog will store information relating assay types to CF programs](../requirements/r00008-r00008-the-catalog-will-store-information-relating-assay-types-to-cf-programs.md)


#### T0009 Summarize FAIRness scores by CF Program X

-   [R00018 The interface will support the selection of a CF Program of interest](../requirements/r00018-the-interface-will-support-the-selection-of-a-cf-program-of-interest.md)
-   [R00019 The C2M2 model will support information relating FAIR metrics to CF programs](../requirements/r00019-the-c2m2-model-will-support-information-relating-fair-metrics-to-cf-programs.md)
-   [R00020 The catalog will store information relating FAIR metrics to CF programs](../requirements/r00020-the-catalog-will-store-information-relating-fair-metrics-to-cf-programs/md)


#### T0008 Summarize FAIRness scores by CF Program X over time

-   [R00018 The interface will support the selection of a CF Program of interest](../requirements/r00018-the-interface-will-support-the-selection-of-a-cf-program-of-interest.md)
-   [R00021 The interface will support the selection of a time period of interest](../requirements/r00021-the-interface-will-support-the-selection-of-a-time-period-of-interest.md)
-   [R00019 The C2M2 model will support information relating FAIR metrics to CF programs](../requirements/r00019-the-c2m2-model-will-support-information-relating-fair-metrics-to-cf-programs.md)
-   [R00020 The catalog will store information relating FAIR metrics to CF programs](../requirements/r00020-the-catalog-will-store-information-relating-fair-metrics-to-cf-programs/md)

#### T0010 Visualize a table of all datasets that match query

-   [R00012 The interface will render tables and plots to display filtered data](../requirements/r00012-the-interface-will-render-tables-and-plots-to-display-filtered-data.md)

#### T0003 Export a file of results

-   [R000014 The interface will support end user download of tables and figures in common formats](../requirements/r000014-the-interface-will-support-end-user-download-of-tables-and-figures-in-common-formats.md)
