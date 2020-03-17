---
layout: default
title: Summary Statistics
nav_order: 3
parent: Summaries
has_children: true
---
# Monitor Data Releases as a Data Custodian

**Persona:** [Data Custodian](../personas/data-custodian).

**Objective:** [Monitor Data Releases](../objectives/single-dcc-release)

# Summary

Janice is the PI for data coordinating center. She would like
to use the CFDE dashboard to help write a progress report for her funding agency.
Using the browse and filter functions on the CFDE portal she creates a report
containing relevant summary statistics for datasets owned by her DCC, and
rendered graphs and figures of the summary data. This includes information such
as how much data is currently publicly available on her portal, how much is
uploaded but embargoed, the FAIRness score for these datasets, and how these
statistics have changed over the previous year.

### User Tasks

-   [Access to CFDE portal](#access-cfde-portal)
-   [Summarize all datatypes hosted by CF Program X](#summarize-all-datatypes-hosted-by-cf-program-x)
-   [Summarize FAIRness scores by CF Program X](#summarize-fairness-scores-by-cf-program-x)
-   [Summarize FAIRness scores by CF Program X over time](#summarize-fairness-scores-by-cf-program-x-over-time)
-   [Visualize a table of all datasets that match query](#visualize-a-table-of-all-datasets-that-match-query)
-   [Export a file of results](#export-a-file-of-results)

### Requirements

#### Access CFDE portal

-   The portal will support GUI web access to end users
-   The portal will support user authentication


#### Summarize all datatypes hosted by CF Program X

-   The portal shall support the selection of a CF Program of interest
-   The C2M2 model shall support information relating datatypes to CF programs
-   The catalog shall store information relating datatypes to CF programs


#### Summarize FAIRness scores by CF Program X

-   The portal shall support the selection of a CF Program of interest
-   The C2M2 model shall support information relating FAIR metrics to CF programs
-   The catalog shall store information relating FAIR metrics to CF programs


#### Summarize FAIRness scores by CF Program X over time

-   The portal shall support the selection of a CF Program of interest
-   The portal shall support the selection of a time period of interest
-   The C2M2 model shall support information relating FAIR metrics to CF programs
-   The catalog shall store information relating FAIR metrics to CF programs


#### Visualize a table of all datasets that match query

-   The portal will render tables and plots to display filtered data


#### Export a file of results

-   The portal shall support end user download of tables and figures in common formats
