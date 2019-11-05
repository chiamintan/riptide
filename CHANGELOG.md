# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 0.0.1 - 2019-11-04
### Fixed
- When normalising TimeSeries, use a float64 accumulator when calculating mean and variance. This avoid saturation issues on data with high values, e.g. from 8-bit Parkes UWL observations.

### Changed
- Improved candidate plots: docstring for `Candidate` class, DM unit on plots, option to subtract the baseline value of the profile before displaying it, option to plot the profile as either a bar or line chart.

## 0.0.1 - 2018-10-25
### Added
- First stable release of riptide. This is the version that will be run on the LOTAAS survey.