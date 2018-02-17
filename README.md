# BitQuery

[BitQuery](http://bitquery.de) is a GitHub API driven and D3 based search engine for open source repositories.

## Description
[BitQuery](http://bitquery.de) pursues two main objectives:

- (I) Provide an automatic OSR categorization system for data science teams and software developers promoting discoverability, technology transfer and coexistence
- (II) Establish visual data exploration and topic driven navigation of GitHub organizations for collaborative reproducible research (CRR) and web deployment

The [BitQuery](http://bitquery.de) architecture consists of three abstraction layers, following the visual analytics approach [(D. Keim, 2008)](https://link.springer.com/chapter/10.1007%2F978-3-540-70956-5_7):

- GitHub API based parser layer (**Data Management**)
- Smart Data layer (**Analysis**)
- D3-3D Visu layer, or BitQuery Visual Analytics application (VA-App) (**Visualization**)

Visual Analytics layouts of [BitQuery](http://bitquery.de) include: 
- [CRAN edition](http://bitquery.de) - visual exploration of the R universe, a massive collection of all R packages on GitHub including [CRAN](https://github.com/cran) and [Bioconductor](https://github.com/Bioconductor)
- [Special edition](http://bitquery.de/spec) - visual data mining of 4 different metadata types: YAML, DCF, JSON, Markdown
- [GitHub edition](http://bitquery.de/github) - interactive visual knowledge discovery of top GitHub organizations
- [HCA Multilevel Edition](http://bitquery.de/hca)
- [Data Projector Edition](http://bitquery.de/dp)

## Presentation of BitQuery at DDSV 2017

Presentation of [BitQuery](http://bitquery.de) at [Data Science, Statistics & Visualization Conference 2017, Lisbon, Portugal](http://iasc-isi.org/dssv2017/):

- [Abstract](dssv2017_abstract.pdf): BitQuery - GitHub API driven and D3 based search engine for open source 
- [Talk](dssv2017_talk.pdf): BitQuery - GitHub API driven and D3 based search engine for open source repositories


## Citing BitQuery

If you use BitQuery in your research or use it for visualizing your repositories on GitHub, please use the following BibTeX entry.

```
@online{BitQuery,
    title = {{BitQuery: a GitHub API driven and D3 based search engine for open source repositories}},
    author = {Lukas Borke and Svetlana Bykovskaya},
    year = {2017},
    url = {http://bitquery.de},
    urldate = {2017-12-01},
    NOTE = {Available at http://bitquery.de},
}
```

If you would like do add new views with more repositories and organizations to BitQuery, please contact the creators of BitQuery:
https://github.com/orgs/bemined/people .
