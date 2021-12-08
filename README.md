# Currency Strength Chart

## v27.0
- Added options "Source", "Calculate by"
- Added options "Histogram" on the "auto selected"
- Added the `if barstate.islast` for performance improvement

Hopefully, performance will not deteriorate 🙏

Example:
Mode: Lookback periods
Lookback periods: 30
Smoothing: SMA/3
Calculated by: Stocastics/7
Auto selected: Yes/Histogram/Ordered


## v26.0
- Improved performance.
- Removed `var`.
- Removed `switch` and `array`

## v25.0
- Removed 2 currencies difference histogram
- Removed plotting barcolor
- Added an option "Auto selected current currencies"
- Added an option "Resolution"
