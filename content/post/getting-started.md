+++
title = "This is a post made it to verify if disqus is working"

date = 2016-04-20T00:00:00
lastmod = 2018-01-13T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = []

tags = []
summary = "Let's go!"

[header]
image = ""
caption = ""

+++

I'm just going to plot something here:

```
data(iris)
head(iris)
plot(Sepal.Length ~ Sepal.Width, data = iris, type = "p")
abline(lm(Sepal.Length ~ Sepal.Width, data = iris), lwd = 1.5, col = "red")
```
