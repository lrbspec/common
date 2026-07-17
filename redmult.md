# `common.redmult`
## descriptions
contains the fractional multipliers for acceleration lines.

every time `base.simline` encounters an acceleration line it reads the next multiplier value from this mod’s list.

## data section
name|type|description|
-|-|-|
count|u64|number of red lines|
multipliers|f64[count]|one double precision float per red line.

## meta
```
name = common.redmult
version = 0
flags = 00010010 // data | physics
```
