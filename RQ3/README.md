Experimental data (Depth of Cross-language Dependencies): [click](https://drive.google.com/drive/my-drive?dmr=1&ec=wgc-drive-hero-goto)


## Table 1 (nodes_all):

* node_lD
* version
* language
* platform
* repository_url
* normalized_licenses
* latest_release_published_at
* repository_license
* project_rank
* project_stars
* PR
* degree_out
* degree_in
* reach_out
* reach_in
* depth
* hubs
* authorities



## SQl Example
* Query the depth of cross-language dependencies for the project.
  
  ```sql
  SELECT depth FROM nodes_all WHERE node_ID = ''
  
