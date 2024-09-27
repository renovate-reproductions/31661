# 31661

Reproduction for [Renovate discussion 31661](https://github.com/renovatebot/renovate/discussions/31661)

## Current behavior

Renovate tries to upgrade numpy to version [2.1.1](https://pypi.org/project/numpy/2.1.1/) even though it is incompatible with the python version `~3.9`.

## Expected behavior

Renovate should upgrade numpy to the lastest valid version which is [2.0.2](https://pypi.org/project/numpy/2.0.2/) relative to the python version declared in the poetry dependencies.

## Link to the Renovate issue or Discussion

[Renovate discussion 31654](https://github.com/renovatebot/renovate/discussions/31661)