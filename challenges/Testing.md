---
title: Test

--- type:OutputChallenge
## Element-wise matrix operations

*** =code
```{r}
x <- {{var1}}
y <- {{var2}}
x {{fun1}} y
x {{fun2}} y
```

*** =variables
var1:
  - matrix(c(2, 4, 6), nrow = 2, ncol = 3)
  - matrix(1, nrow = 3, ncol = 1)
  - 10
  - matrix(c(1, 2, 4), nrow = 2, ncol = 3)
var2:
  - matrix(c(2, 1), nrow = 2, ncol = 3)
  - matrix(2, nrow = 1, ncol = 3)
  - matrix(c(1, 2, 4), nrow = 1, ncol = 3)
  - matrix(c(4, 2, 1), nrow = 2, ncol = 3)
fun1:
  - +
  - "-"
fun2:
  - /
  - "*"
