Homework \#1 – Pet Names Dataset
================
Ryam Radi M
2021-02-17

**Student ID: 2201001476 **

**Deadline:** 23:59 on Saturday, 13 February 2021

**Total Points:** 30

## Loading Packages

``` r
library(tidyverse)
library(openintro)
library(ggrepel)
```

\#\#Exercises

\`1.how many pets are included in this dataset ?

(4 points)

> 1.  519

\`2.how many variables do we have for each pet ?

(4 points)

> variables: 7

\`3. Copy the code provided in the homework documentation and paste it
here .

# A tibble: 13,930 x 2

animal\_name n <chr> <int> 1 NA 483 2 Lucy 439 3 Charlie 387 4 Luna 355
5 Bella 331 6 Max 270 7 Daisy 261 8 Molly 240 9 Jack 232 10 Lily 232 \#
.. with 13,920 more rows

# A tibble: 16,823 x 3

# Groups: species \[4\]

species animal\_name n <chr> <chr> <int> 1 Cat NA 406 2 Dog Lucy 337 3
Dog Charlie 306 4 Dog Bella 249 5 Dog Luna 244 6 Dog Daisy 221 7 Dog
Cooper 189 8 Dog Lola 187 9 Dog Max 186 10 Dog Molly 186 \# … with
16,813 more rows

# A tibble: 4 x 2

species n <chr> <int> 1 Dog 35181 2 Cat 17294 3 Goat 38 4 Pig 6

(4 points)

Write your narrative here

\`4.. \# A tibble: 53 x 3 \# Groups: species \[4\] species animal\_name
n <chr> <chr> <int> 1 Cat NA 406 2 Cat Luna 111 3 Cat Lucy 102 4 Cat
Lily 86 5 Cat Max 83 6 Dog Lucy 337 7 Dog Charlie 306 8 Dog Bella 249 9
Dog Luna 244 10 Dog Daisy 221 \# … with 43 more rows

(10 points)

\`5. What names are more common for cats than dogs? The ones above the
line or the ones below the line ?

Oliver and lily

(4 points)

\`6. Is the relationship between the two variables (proportion of cats
with a given name and proportion of dogs with a given name) positive or
negative? What does this mean in context of the data ?

Poitive,if the names of the dogs increased, the names of the cats
increased, and if the names of the dogs decreased, the names of the cats
also decreased.

(4 points)
