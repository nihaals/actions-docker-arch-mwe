# GitHub Actions Arch Linux Docker issue MWE

This issue started between 2021-02-06 08:14 UTC and 2021-02-06 09:12 UTC.

This issue was fixed between 2021-03-04 00:24 UTC and 2021-03-05 00:25 UTC.

The main issue for this problem is [actions/virtual-environments#2658](https://github.com/actions/virtual-environments/issues/2658).

## Steps to reproduce

1. Clone this repository
2. Run `docker build .`
3. Notice it works
4. Check the [Actions log](https://github.com/nihaals/actions-docker-arch-mwe/actions?query=workflow%3ABuild) and notice it fails to build

If you want to experiment, I recommend forking this repo and making changes.
