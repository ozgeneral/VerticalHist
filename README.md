# VerticalHist
R function to create vertical histograms

Example use:

```
data <- as.data.frame(matrix(c(rep(rnorm(500, 110, 20),5)), ncol=5, byrow=TRUE))
VerticalHistCaller(data)
```


_ Based on [this](stackoverflow.com/a/13334294/903061) Stack Overflow answer created by Gregor Thomas_


