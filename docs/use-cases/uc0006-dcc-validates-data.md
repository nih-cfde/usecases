---
layout: default
title: UC0006 DCC validates data
nav_order: 6
parent: Use Cases
has_children: false
---
# Use Case UC0006 DCC approves data

**Persona:** [Data Custodian](../personas/data-custodian.md)

**Objective:** [Approve data](../objectives/view-existing-data.md)

### Summary

Kristin would like to view the metadata associated with her DCC that currently exists
in the CFDE portal.

She logs into the portal using an existing identity, which takes her to
a restricted page showing summary statistics about what data her DCC currently has
in the portal. This display helps her answer questions like:

-   How many data files exist for her DCC overall
-   How many subjects are represented
-   How many and which data types are represented
-   How many and which anatomy terms are represented
-   What Project names are associate with her DCC
-   Number of biosamples in those Projects
-   Number of data_type in those Projects

By comparing the summary statistics supplied by the interface, Kristin can determine
whether the data currently available at the CFDE is up to date with her current
internal data holdings, and decide whether to start a new metadata ingest.


### User Tasks

-   [T0001 Access CFDE interface](../user-tasks/t0001-access-cfde-interface.md)
-   [T0007 Summarize all assay types hosted by CF Program X](../user-tasks/t0007-summarize-all-datatypes-hosted-by-cf-program-x.md)
-   [T0017 Summarize all anatomy terms hosted by CF Program X](../user-tasks/t0017-summarize-all-anatomy-terms-hosted-by-cf-program-x.md)
-   [T0018 Summarize all projects hosted by CF Program X](../user-tasks/t0018-summarize-all-subjects-hosted-by-cf-program-x.md)
-   [T0019 Summarize all subjects hosted by CF Program X](../user-tasks/t0019-summarize-all-subjects-hosted-by-cf-program-x.md)

### Requirements

#### T0001 Access CFDE interface

-   [R00001 The interface will support GUI web access to end users](../requirements/r00001-the-interface-will-support-gui-web-access-to-end-users.md)
-   [R00002 The interface will support user authentication](../requirements/r00002-the-interface-will-support-user-authentication.md)
-   [R00034 The interface will support linking an SSO identity to an organization profile](../requirements/r00034-the-interface-will-support-linking-an-sso-identity-to-an-organization-profile.md)

#### T0007 Summarize all assay types hosted by CF Program X

-   [R00007 The C2M2 model will support information relating assay types to CF programs](../requirements/r00007-the-c2m2-model-will-support-information-relating-assay-types-to-cf-programs.md)
-   [R00008 The catalog will store information relating assay types to CF programs](../requirements/r00008-the-catalog-will-store-information-relating-assay-types-to-cf-programs.md)


#### T0017 Summarize all anatomy terms hosted by CF Program X

-   [R00004 The C2M2 model will support information relating Uberon terms to CF programs](../requirements/r00004-the-c2m2-model-will-support-information-relating-uberon-terms-to-cf-programs.md)
-   [R00005 The catalog will store information relating Uberon terms to CF programs](../requirements/r00005-the-catalog-will-store-information-relating-uberon-terms-to-cf-programs.md)

#### T0018 Summarize all projects hosted by CF Program X

-   [R00010 The catalog will store information relating projects to CF programs](../requirements/r00010-the-catalog-will-store-information-relating-projects-to-cf-programs.md)
-   [R00011 The C2M2 model will support information relating projects to CF programs](../requirements/r00011-the-c2m2-model-will-support-information-relating-projects-to-cf-programs.md)

#### T0019 Summarize all subjects hosted by CF Program X

-   [R00035 The catalog will store information relating subjects to CF programs](../requirements/r00035-the-catalog-will-store-information-relating-subjects-to-cf-programs.md)
-   [R00036 The C2M2 model will support information relating subjects to CF programs](../requirements/r00036-the-c2m2-model-will-support-information-relating-subjects-to-cf-programs.md)
