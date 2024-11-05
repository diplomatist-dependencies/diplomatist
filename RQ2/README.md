We deployed *Diplomatist* to iteratively analyze 612,249 Java projects from the *Maven* ecosystem, all of which were the latest released versions dated January 1, 2024.

Download: [click](https://drive.google.com/drive/my-drive?dmr=1&ec=wgc-drive-hero-goto)

We upload all our experimental data to Google Drive. The size of the SQL files is excessively large.

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

## Table 2 (cross-language dependencies)
* project_name
* category
* dependency_name
* version_requirement
* version_had
* version
  
## Table 3 (dependencies between same languages)
* ini_node
* goal_node
* edge_node

## SQl Example
* Query all information about the project.
  
  ```sql
  SELECT * FROM nodes_all WHERE node_ID = ''
  
* Query cross-language dependencies of the project.
  
  ```sql
  SELECT * FROM jar_dependencies WHERE project_name = ''

* Query dependencies between same languages.

  ```sql
  SELECT * FROM nodes_dependencies_all WHERE ini_node = ''

