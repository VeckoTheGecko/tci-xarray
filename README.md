# Tensor Cross Interpolation within Xarray

This repo is an exploration of the applications of [Tensor Cross Interpolation](https://inspirehep.net/literature/2804096) for use in Xarray.

Contributors:

- @TakisAngelides: currently doing research related to the TCI algorithm
- @VeckoTheGecko: familiar with Xarray, and the Pangeo community/software

## Dev setup

- [Install pixi](https://pixi.sh/dev/installation/)
- Run `pixi shell` to enter the environment for this project (this will have all deps installed, allowing you to go into (e.g.,) jupyter lab). Run `exit` in the terminal to exit this environment.
- (optional) run `pixi shell` then `pre-commit install` to install the pre-commit hooks for this project. Now every time you commit, automatic checks are run against your code (defined in `.pre-commit-config.yaml`). This is optional since these checks are already run and applied on GitHub in CI.

## Contributing

PRs are prefered (even if you are just self merging them). Easier than just committing to `main`.
