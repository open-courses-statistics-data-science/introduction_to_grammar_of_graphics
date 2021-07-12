# Introduction to scalable visualisation using the grammar of graphics paradigm
This course provides a half day introduction to visualisation using the grammar of graphics approach. In the course, participants will learn:

- how the traditional approach to visualisation differs to the grammar of graphics one
- what aesthetics and geoms are
- how grammar of graphics allows for agile exploration of hierarchical datasets

The course consists of a short [lecture](https://htmlpreview.github.io/?https://github.com/ben18785/introduction_to_grammar_of_graphics/blob/main/presentations/grammar_of_graphics_visualisation.html) and a problem set. The lecture uses [country-level reported suicide rates data](https://www.kaggle.com/russellyates88/suicide-rates-overview-1985-to-2016) to illustrate how grammar of graphics approaches work.

The exercise within the [problem set](./problem_sets/gapminder.ipynb) invites participants to visualise [gapminder data](./problem_sets/data/gapminder.csv). Answers to this problem set (written in Python) are available [here](./problem_sets/answers/gapminder.ipynb).

## References

The best reference for this course is the ggplot2 book by Hadley Wickham, Danielle Navarro, and Thomas Lin Pedersen which is [freely available online](https://ggplot2-book.org/). The whole book is great (and not that long). But, I'd especially recommend the following chapters for someone new to ggplot:

- [introduction](https://ggplot2-book.org/introduction.html)
- [first steps](https://ggplot2-book.org/getting-started.html)
- [individual](https://ggplot2-book.org/individual-geoms.html) and [collective](https://ggplot2-book.org/collective-geoms.html) geoms
- [statistical uncertainties](https://ggplot2-book.org/statistical-summaries.html)
- [scales](https://ggplot2-book.org/scale-position.html)
