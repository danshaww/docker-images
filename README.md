## Docker Images Repository  
  
This repository contains my custom docker images, with individual projects stored in sub directories.  
  
All changes must be made on feature branches, and then merged into the main branch via a pull request.  
  
Images are built & deployed to my infrastructure using GitHub Actions, any push to a feature branch will trigger the workflow and deploy to the dev environment only, merges to the main branch will trigger both the dev & production stages of the pipeline, deploying to both environments.
  
Images are build and stored as GitHub Packages.  