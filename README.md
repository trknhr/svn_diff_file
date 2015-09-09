# svn_diff_file
Extract diff files from before version in SVN by ant task

## Settings

1. Install `svn_diff_file`.

  ```sh
  git clone https://github.com/1984weed/svn_diff_file
  ```
  
2. Set property file
you set build.properties key value.

* `repoUrl`: your target svn url (http or https)

* `before_revision`: get files which HEAD in ```repoURLget``` are different files from before_revision

* `include_path`: you want to get files in (include_path) directory.

* `outdir`: extract files are destination
