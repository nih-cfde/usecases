### Epic
Obtain data to help describe research opportunities (e.g., for a grant), apply for dbGaP, or pass on to computational biologists for analysis.
 
### User Story
As a naïve user, I want to use the CFDE portal to access datasets owned by different DCCs and filter down to the results that will be relevant to my biological question (including filtering for data from the same disease or tissue).
 
### Actors
Pam: Pam understands the biology of a disease, but has low computational literacy. She will primarily interact with the data via a point-and-click interface and will very rarely work with the data files herself (but should have the option to). She is most interested in navigating the data in an intuitive way, viewing and saving summary statistics in the form of automatically rendered graphs and figures, and creating lists of data files to share with herher computational colleague.
 
### Preconditions
* User is interested in accessing and analyzing data across DCCs.
 
### Scenario: Browsing and Filtering
Pam is a postdoc working in a lab that studies the thyroid. She is interested in collaborating with a computational biologist to analyze datasets from a variety of studies for evidence of an association with thyroid disorders. She would like to use the CFDE portal to browse and filter  metadata and summary statistics for datasets in order to find suitable studies for her analysis. She would like to see summary metadata and quickly download automatically rendered plots she can use in a PowerPoint presentation she is planning to prepare for the next lab meeting. She also wants to download a table containing both the summarized metadata and the names of the associated files which can be shared with her collaborator.

### Workflow
1. The user will be able to access basic functionalities of the website without creating an account.
2. The user will be able to filter by summarizable metadata (e.g., age of onset, N of dataset, N of data types, data types).
3. The user will be able to dynamically interact with data plots and easily perform tasks such as adding a data field as a filter
4. The user will be able to easily view data statistics (e.g., N=46).
5. The user will be able to switch between a plot view and a table view of the filtered metadata. 
6. The user will be able to dynamically interact with data tables and easily perform tasks such as sorting by column headers.
7. The user will be able to view additional, non-summarizable public metadata fields (e.g., SubjectID, FileName) indata tables.
8. The user will be able to view and directly edit her search queries.
9. The user will be able to download or save queries to her profile for reuse later.
10. The user can easily push the filtered list of studies to a cloud workspace where she and others authorized to access the workspace (e.g., computational biologist) will have access to it.
 
### Postconditions
* The user has automatically rendered plots for use in his or her PowerPoint presentation.
* The user has summarized metadata and the names of the files it is based on.

### Notes
The design and functionality inspiration for this use case is the Kids First search portal:
![kids first search portal screenshot](https://github.com/nih-cfde/public-website-content/blob/master/images/kids-first-dashboard.png)
