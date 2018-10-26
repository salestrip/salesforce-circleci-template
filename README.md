# CircleCI Build Script - sfdx

A template YAML build script for [CircleCI](http://circleci.com) which includes steps to:

1. Authenticate with an Org
2. Lint code
3. Create a scratch Org
4. Deploy to an Org
5. Install a managed package
6. Run Apex tests
7. Delete a scratch Org
8. Combine all or some of the above

You'll also see a reference to [a Docker image we've created](https://github.com/salestrip/docker-sfdx-cli) that contains everything you need to run SFDX on CI servers that support Docker.
