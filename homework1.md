Homework \#1 – Pet Names Dataset
================
Ryam Radi
2021-02-15

**Student ID: 2201001476**

**Deadline:** 23:59 on Saturday, 13 February 2021

**Total Points:** 30

## Loading Packages

``` r
library(tidyverse)
library(openintro)
library(ggrepel)
```

\#\#Exercises

\`1.how many pets are included in this dataset?

(4 points)

> 52.519

\`2.how many variables do we have for each pet?

(4 points)

> variables:7

\`3. Copy the code provided in the homework documentation and paste it
here. &gt;seattlepets %&gt;% count(animal\_name, sort = TRUE)

> seattlepets %&gt;% group\_by(species) %&gt;% count(animal\_name, sort
> = TRUE)

> seattlepets %&gt;% count(species, sort = TRUE)

(4 points)

Write your narrative here

\`4. &gt;seattlepets %&gt;% group\_by(species) %&gt;%
count(animal\_name, sort = TRUE) %&gt;% slice\_max(n, n = 5) %&gt;%
arrange(species, n)

(10 points)

\`5. What names are more common for cats than dogs? The ones above the
line or the ones below the line?

Oliver and lily

(4 points)

\`6. Is the relationship between the two variables (proportion of cats
with a given name and proportion of dogs with a given name) positive or
negative? What does this mean in context of the data?

Answer here

(4 points)
