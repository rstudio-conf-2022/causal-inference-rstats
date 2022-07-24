
<!-- README.md is generated from README.Rmd. Please edit that file -->

## Causal Inference in R Workshop

:spiral_calendar: July 25 and 26, 2022  
:alarm_clock: 09:00 - 17:00  
:hotel: National Harbor 3  
:writing_hand: [rstd.io/conf](http://rstd.io/conf)

### Slides

-   [00
    Intro](https://causal-inference-r-workshop.netlify.app/00-intro.html)
-   [01 Whole
    Game](https://causal-inference-r-workshop.netlify.app/01-causal_modeling_whole_game.html)
-   [02 When Standard Methods
    Succeed](https://causal-inference-r-workshop.netlify.app/02-when-standard-methods-succeed.html)
-   [03 Causal Inference with `group_by` and
    `summarise`](https://causal-inference-r-workshop.netlify.app/03-causal-inference-with-group-by-and-summarise.html)
-   [04 Causal
    Diagrams](https://causal-inference-r-workshop.netlify.app/04-dags.html)
-   [05 Introduction to Propensity
    Scores](https://causal-inference-r-workshop.netlify.app/05-pscores.html)
-   [06 Using Propensity
    Scores](https://causal-inference-r-workshop.netlify.app/06-using-pscores.html)
-   [07 Checking Propensity
    Scores](https://causal-inference-r-workshop.netlify.app/07-pscore-diagnostics.html)
-   [08 Fitting the outcome
    model](https://causal-inference-r-workshop.netlify.app/08-outcome-model.html)
-   [09 Continuous
    Exposures](https://causal-inference-r-workshop.netlify.app/09-continuous-exposures.html)
-   [10
    G-Computation](https://causal-inference-r-workshop.netlify.app/10-g-computation.html)
-   [11 Tipping Point Sensitivity
    Analyses](https://causal-inference-r-workshop.netlify.app/11-tipr.html)
-   [12 Whole Game (Your
    Turn)](https://causal-inference-r-workshop.netlify.app/12-whole_game-2.html)

### Installing materials locally

We will be using RStudio Cloud for the workshop, but if you would like
to install the required packages and course materials, we have an R
package called
{[causalworkshop](https://github.com/malcolmbarrett/causalworkshop)} to
help you do that! You can install
{[causalworkshop](https://github.com/malcolmbarrett/causalworkshop)}
from GitHub with:

``` r
install.packages("remotes")
remotes::install_github("malcolmbarrett/causalworkshop")
```

Once you’ve installed the package, install the workshop with

``` r
causalworkshop::install_workshop()
```

By default, this package downloads the materials to a conspicuous place
like your Desktop. You can also tell `install_workshop()` exactly where
to put the materials:

``` r
causalworkshop::install_workshop("a/path/on/your/computer")
```

## Schedule

### Day 1

| Time          | Activity       |
|:--------------|:---------------|
| 09:00 - 10:30 | Session 1      |
| 10:30 - 11:00 | *Coffee break* |
| 11:00 - 12:30 | Session 2      |
| 12:30 - 13:30 | *Lunch break*  |
| 13:30 - 15:00 | Session 3      |
| 15:00 - 15:30 | *Coffee break* |
| 15:30 - 17:00 | Session 4      |

### Day 2

| Time          | Activity       |
|:--------------|:---------------|
| 09:00 - 10:30 | Session 1      |
| 10:30 - 11:00 | *Coffee break* |
| 11:00 - 12:30 | Session 2      |
| 12:30 - 13:30 | *Lunch break*  |
| 13:30 - 15:00 | Session 3      |
| 15:00 - 15:30 | *Coffee break* |
| 15:30 - 17:00 | Session 4      |

## Instructor

Lucy D’Agostino McGowan is an assistant professor in the Mathematics and
Statistics Department at Wake Forest University. She received her PhD in
Biostatistics from Vanderbilt University and completed her postdoctoral
training at Johns Hopkins University Bloomberg School of Public Health.
Her research focuses on statistical communication, causal inference,
data science pedagogy, and human-data interaction. Dr. D’Agostino
McGowan is the past chair of the American Statistical Association’s
Committee on Women in Statistics, chair elect for the Section on
Statistical Graphics, and can be found blogging at
livefreeordichotomize.com, on Twitter @LucyStats, and podcasting on the
American Journal of Epidemiology partner podcast, Casual Inference.

Malcolm Barrett is a data scientist and an epidemiologist. During his
Ph.D., he studied vision loss, focusing on epidemiologic methods. He’s
since worked in the private sector, including Teladoc Health and Apple.
Malcolm is also the author of several causal inference-focused R
packages, such as ggdag and tidysmd. He regularly contributes to other
open source software, including favorite community projects like
usethis, ggplot2, R Markdown.

------------------------------------------------------------------------

![](https://i.creativecommons.org/l/by/4.0/88x31.png) This work is
licensed under a [Creative Commons Attribution 4.0 International
License](https://creativecommons.org/licenses/by/4.0/).
