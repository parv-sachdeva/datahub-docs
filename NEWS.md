# NEWS

### v1.2.0 (2023-07-18)

* Database as an isolated service
* Automatic database backups (1d, 1w, 30days)
* rnaApp
  * Add GSEA module using genelists in datahub
  * Showcase differentially expressed genes in the datahub genelists
  * Free scale plots in differential expression
* Capture timestamps in database tables
* Add dataset short names using the format `{dataset_owner}_{year_yy}{month_mm}`

### v1.1.0 (2023-06-07)

* added Okta based user authentication
* detached database as a separate independent service
* update bulkRNA app with Genelist heatmap UI
* added 2023-06\_sydney\_activationkinetics dataset in bulkRNA app

### V0.4.0 (2023-03-07)

* implemented the basic password protection
* added the MSD cytokine app

### v0.3.3 (2023-02-15)

* update Healthy Tissue app
* adds 7200 target ID function
* Healthy Tissue app data moved to s3, layer download in dockerfile

### v0.3.2 (2023-02-09)

* update IBD app to v0.2.0 (includes Kanke 2023 CD dataset)
* example process for using s3

### v0.3.1 (2023-01-23)

* Mv IBD app's installation to dockfile

### v0.3.0 (2023-01-11)

* Added IBD app

### v0.2.1 (2023-01-11)

* update the scApp (7101 data) by changing the 'resting treg' to 'effector treg'

### v0.2 (2022-12-07)

* Added scATAC app (for Frederic's data)

### v0.1 (2022-10-22)

* Initial launching with 2 services/apps: Target I.D and scRNA visualization (python).
* Presented at the IMPACT meeting
