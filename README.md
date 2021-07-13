# A short introduction to grammar of graphics (via ggplot2)
This course provides a half day introduction to visualisation in R and Python using the grammar of graphics approach. In the course, participants will learn:

- how the traditional approach to visualisation differs to the grammar of graphics one
- what aesthetics and geoms are
- how grammar of graphics allows for agile exploration of hierarchical datasets

The course consists of a [series of short lectures](https://www.youtube.com/playlist?list=PLwJRxp3blEvaYRYWTqQ5ScIow8ZBm3Q92) and a problem set. The lectures use [country-level reported suicide rates data](https://www.kaggle.com/russellyates88/suicide-rates-overview-1985-to-2016) to illustrate how the grammar of graphics approach works.

The exercise within the [problem set](./problem_sets/gapminder.ipynb) invites participants to visualise [gapminder data](./problem_sets/data/gapminder.csv). Answers to this problem set (written in Python) are available [here](./problem_sets/answers/gapminder.ipynb).

## Prerequisites
The course doesn't really have any! I give two really simple "base R" plots in the lecture, but these types of plots are very similar in other languages, like Python or Matlab. All that you need is an interest in plotting data.

## References
The best reference for this course is the ggplot2 book by Hadley Wickham, Danielle Navarro, and Thomas Lin Pedersen which is [freely available online](https://ggplot2-book.org/). The whole book is great (and not that long). But, I'd especially recommend the following chapters for someone new to ggplot:

- [introduction](https://ggplot2-book.org/introduction.html)
- [first steps](https://ggplot2-book.org/getting-started.html)
- [individual](https://ggplot2-book.org/individual-geoms.html) and [collective](https://ggplot2-book.org/collective-geoms.html) geoms
- [statistical uncertainties](https://ggplot2-book.org/statistical-summaries.html)
- [scales](https://ggplot2-book.org/scale-position.html)
- [faceting](https://ggplot2-book.org/facet.html)
- [themes](https://ggplot2-book.org/polishing.html)

Another book I'd recommend, more generally, is [The visual display of quantitative information](https://www.amazon.co.uk/Visual-Display-Quantitative-Information/dp/0961392142) by Tufte. It's a beautifully crafted book with lots of excellent visualisations. My one issue with it is that, in my view, it occasionally advocates for style over substance: resulting in visualisations that look great but that perhaps don't provide as much insight as they could.
