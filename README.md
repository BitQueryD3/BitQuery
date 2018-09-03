# BitQuery

[BitQuery](http://bitquery.de) is a **GitHub API driven and D3 based search engine for open source repositories**.

## Description
[BitQuery](http://bitquery.de) pursues three main objectives:

- (I) Query the repository metadata via text mining and clustering methods, thus providing an automatic categorization system for software developers
- (II) Establish visual data exploration and topic driven navigation of GitHub repositories for more transparency in source code management
- (III) Promote discoverability and technology transfer for data science and project teams

The [BitQuery](http://bitquery.de) architecture consists of three abstraction layers, following the visual analytics approach [(D. Keim, 2008)](https://link.springer.com/chapter/10.1007%2F978-3-540-70956-5_7):

- GitHub API based parser layer (**Data Management**)
- Smart Data layer (**Analysis**)
- D3-3D Visu layer, or BitQuery Visual Analytics application (VA-App) (**Visualization**)

Visual Analytics layouts of [BitQuery](http://bitquery.de) include:
- [Special edition](http://bitquery.de/spec) - Visual data mining of open source libraries, package networks and other well-documented data collections. The following metadata types are supported: JSON, YAML, DCF and Markdown.
- [CRAN edition](http://bitquery.de/cran) - Explore and query the R universe, a comprehensive collection of R packages on GitHub including both the official [CRAN](https://github.com/cran) packages and the developer versions.
- [GitHub edition](http://bitquery.de/github) - Explore and query GitHub organizations. At present, there are more than one million organizations on GitHub, among them
[Amazon Web Services](https://github.com/aws), [Microsoft Azure](https://github.com/Azure), [Google Cloud Platform](https://github.com/GoogleCloudPlatform) and many more.
- [HCA Multilevel Edition](http://bitquery.de/hca) (Beta (but working) version for various CRAN and Organizations data sets)
- [Data Projector Edition](http://bitquery.de/dp) (experimental Three.js Visualization)

## Introduction

- [BitQuery Intro](BitQueryIntro.pdf)

## First presentation of BitQuery at DSSV 2017

Presentation of [BitQuery](http://bitquery.de) at [Data Science, Statistics & Visualization Conference 2017, Lisbon, Portugal](http://iasc-isi.org/dssv2017/):
- [BitQuery Slides](dssv2017_talk.pdf)

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

If you would like to add new views with more repositories and organizations to BitQuery, please contact the creators of BitQuery: https://github.com/orgs/bemined/people .
