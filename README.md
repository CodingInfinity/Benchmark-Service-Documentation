# Version Control
This repository has adopted the [git flow branching model](http://nvie.com/posts/a-successful-git-branching-model/). The creators of git flow released a [short intro video](http://vimeo.com/16018419) to explain the model.

The `master` branch is production-ready and contains the latest tagged releases. Before a release is made, it is stagged in `release/x` branches before being pushed and tagged in the `master` branch. Small patches from `hotfix/x` branches are also pushed to `master`, and will always have a release version. The `develop` branch is pre-production, and is where we push `feature/x` branches for testing.

Most modern git clients support git flow. If you are however using the git CLI on *nix, please install the git flow plugin on your distribution.

##For more information please read the wiki
https://github.com/CodingInfinity/Benchmark-Service-Documentation/wiki