R We The People?
----------------

An R Package for working with We The People petition data.

The package is focused on ad-hoc analysis and exploratory
visualizations. While it does contain a small data sample
to ease development, it assumes you're using other tools to
source the data (e.g. `curl` or the [`we_the_people`](https://github.com/yoni/we_the_people) Ruby Gem).

Usage
-----

    install.package('wethepeople')

    library(wethepeople)
    example(wethepeople)

Examples Images
---------------

In addition to the R package examples, there are pregenerated images from a sample of petitions:

h4. Petition Issues Over Time
![issues](examples/issues_over_time.png)

h4. Petition Title Word Cloud
![title wordcloud](examples/title_wordcloud.png)

h4. Petition Body Word Cloud
![body wordcloud](examples/body_wordcloud.png)