# Changelog

## simtrial-python 0.0.1

### New features

- Added a piecewise exponential sampler that mirrors the R implementation using
  inverse-CDF sampling with reproducibility hooks and type hints.

### Testing

- Added pytest tests with 100% code coverage for the sampler, including
  validation, broadcasting, and RNG behaviors.
- Added deterministic R-generated fixtures (`tests/fixtures/`) to
  cross-check Python draws.
