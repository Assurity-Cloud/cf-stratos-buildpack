# stratos-buildpack
Custom buildpack for Stratos for Cloud Foundry.

Stratos (https://github.com/Assurity-Cloud/stratos) consists of a JavaScript front-end and a Go back-end. 

In order to build the UI when pushing to Cloud Foundry, this custom buildpack is used to build both the front-end and the back-end.

This buildpack installs the following prerequisites:

1. GO 1.21.5
2. Node.js

