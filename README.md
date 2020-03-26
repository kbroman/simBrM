
# simBrM

R package to simulate and plot Brownian motion.

## Installation

Install with the devtools package:

```r
devtools::install_github("kbroman/simBrM")
```

## Example

Use `simBrM()` to simulate and `plotBrM()` to plot the result.

```r
library(simBrM)
x <- simBrM(1000)
plotBrM(x)
```

