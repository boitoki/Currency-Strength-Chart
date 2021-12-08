# Currency Strength Chart

## v27.0
- Added options "Source", "Calculate by"
- Added options "Histogram" on the "auto selected"
- Added the `if barstate.islast` for performance improvement
<br>
Hopefully, performance will not deteriorate 🙏<br>
<br>
Example:<br>
Mode: Lookback periods<br>
Lookback periods: 30<br>
Smoothing: SMA/3<br>
Calculated by: Stocastics/7<br>
Auto selected: Yes/Histogram/Ordered<br>


## v26.0
- Improved performance.
- Removed `var`.
- Removed `switch` and `array`

## v25.0
- Removed 2 currencies difference histogram
- Removed plotting barcolor
- Added an option "Auto selected current currencies"
- Added an option "Resolution"
