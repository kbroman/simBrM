
# simBrM

R package to simulate and plot Brownian motion, written to illustrate R package development, as part of the course [Advanced Data Analysis](https://kbroman.org/AdvData).


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

