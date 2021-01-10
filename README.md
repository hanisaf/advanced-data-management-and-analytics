UY
# Launch with Binder

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/hanisaf/advanced-data-management-and-analytics/master)

# Installation instructions

Install the required packages and resources using:

```
pip install -r requirements.txt
python -m textblob.download_corpora
python -m spacy download en
```

# Advanced Data Management and Analytics Topics

|  #  |             Theme             |                 Topics                  |                                                                                                 Readings                                                                                                 |                                                                                                              Video Lectures                                                                                                              |
| --- | ----------------------------- | --------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 01  |                               | Course introduction                     | [JOUR.1](https://www.academia.edu/33249922/Should_You_Pursue_a_Career_in_BI_Analytics), [WTOP.1](https://jakevdp.github.io/WhirlwindTourOfPython/00-introduction.html)                                   | [Course Introduction](https://www.youtube.com/watch?v=XgVlEErvTGc)                                                                                                                                                                       |
| 02  |                               | Markdown language                       | [WEB.0](https://guides.github.com/features/mastering-markdown/), [WTOP.2](https://jakevdp.github.io/WhirlwindTourOfPython/01-how-to-run-python-code.html)                                                | [Introduction](https://www.youtube.com/watch?v=aEBa-AKYfko) [Warmup](https://www.youtube.com/watch?v=KhXL6PrceMM) [Workout](https://www.youtube.com/watch?v=iDcLtmgKQQI)                                                                 |
| 03  | Python language fundamentals  | Variables                               | [WTOP.3](https://jakevdp.github.io/WhirlwindTourOfPython/02-basic-python-syntax.html), [WTOP.4](https://jakevdp.github.io/WhirlwindTourOfPython/03-semantics-variables.html)                             | [Introduction](https://www.youtube.com/watch?v=iXkMAFvhgqk) [Warmup](https://www.youtube.com/watch?v=eJD-Uu-rEhE) [Workout](https://www.youtube.com/watch?v=DPusM5pn_Us)                                                                 |
| 04  |                               | Operators                               | [WTOP.5](https://jakevdp.github.io/WhirlwindTourOfPython/04-semantics-operators.html)                                                                                                                    | [Introduction](https://www.youtube.com/watch?v=Mh7hT92B0Qw) [Warmup](https://www.youtube.com/watch?v=mChZ2wK_kmg) [Workout](https://www.youtube.com/watch?v=z2nMP02wgJc)                                                                 |
| 05  |                               | Types                                   | [WTOP.6](https://jakevdp.github.io/WhirlwindTourOfPython/05-built-in-scalar-types.html)                                                                                                                  | [Introduction](https://www.youtube.com/watch?v=lIkkGlUAaTQ) [Warmup](https://www.youtube.com/watch?v=SbjIqJOI1NM) [Workout](https://www.youtube.com/watch?v=fM7fFQDLJZg)                                                                 |
| 06  |                               | String                                  | [WTOP.15](https://jakevdp.github.io/WhirlwindTourOfPython/14-strings-and-regular-expressions.html)                                                                                                       | [Introduction](https://www.youtube.com/watch?v=O4U1CmWTtbI) [Warmup](https://www.youtube.com/watch?v=wzzgfqd43fk) [Workout](https://www.youtube.com/watch?v=lFPd_RywH74)                                                                 |
| 07  |                               | Control flow                            | [WTOP.8](https://jakevdp.github.io/WhirlwindTourOfPython/07-control-flow-statements.html)  [WTOP.10](https://jakevdp.github.io/WhirlwindTourOfPython/09-errors-and-exceptions.html)                      | [Introduction](https://www.youtube.com/watch?v=xN-Okw-gLRg) [Warmup](https://www.youtube.com/watch?v=LvNvLcbtmws) [Workout](https://www.youtube.com/watch?v=Sep6LQxwubY)                                                                 |
| 08  |                               | Functions                               | [WTOP.9](https://jakevdp.github.io/WhirlwindTourOfPython/08-defining-functions.html)                                                                                                                     | [Introduction](https://www.youtube.com/watch?v=mmXawzBGhFI) [Warmup](https://www.youtube.com/watch?v=dCDmkMd539A) [Workout](https://www.youtube.com/watch?v=WLmVdupGluk)                                                                 |
| 09  | Data manipulation with Python | Built-in data structures                | [WTOP.7](https://jakevdp.github.io/WhirlwindTourOfPython/06-built-in-data-structures.html)                                                                                                               | [Introduction](https://www.youtube.com/watch?v=xxFUxggxFOI) [Warmup](https://www.youtube.com/watch?v=d7IN5-hx78Q) [Workout](https://www.youtube.com/watch?v=x6ERWmDIftA)                                                                 |
| 10  |                               | List comprehensions                     | [WTOP.12](https://jakevdp.github.io/WhirlwindTourOfPython/11-list-comprehensions.html)                                                                                                                   | [Introduction](https://www.youtube.com/watch?v=xz9VsGTOwlY) [Warmup](https://www.youtube.com/watch?v=QlyNDM98d7k) [Workout](https://www.youtube.com/watch?v=Hun1pZb6_3k)                                                                 |
| 11  |                               | Regular expressions                     | [WTOP.15](https://jakevdp.github.io/WhirlwindTourOfPython/14-strings-and-regular-expressions.html)                                                                                                       | [Introduction](https://www.youtube.com/watch?v=uoLesrS8mZw) [Warmup](https://www.youtube.com/watch?v=_WEjBUFdqyA) [Workout](https://www.youtube.com/watch?v=SAEWwAHcQz8)                                                                 |
| 12  |                               | Generators and generator expressions    | [WTOP.13](https://jakevdp.github.io/WhirlwindTourOfPython/12-generators.html)                                                                                                                            | TBD                                                                                                                                                                                                                                      |
| 13  |                               | Modules and packages                    | [WTOP.14](https://jakevdp.github.io/WhirlwindTourOfPython/13-modules-and-packages.html)                                                                                                                  | TBD                                                                                                                                                                                                                                      |
| 14  | Data organization with Pandas | DataFrame and Series                    | [PDSH.3.1](https://jakevdp.github.io/PythonDataScienceHandbook/03.01-introducing-pandas-objects.html)                                                                                                    | [Introduction](https://www.youtube.com/watch?v=NwbsxtZ2Ar0) [Warmup](https://www.youtube.com/watch?v=3MV73a4K7WQ) [Workout](https://www.youtube.com/watch?v=Gd__D4PKm3k)                                                                 |
| 15  |                               | Data indexing and selection             | [PDSH.3.2](https://jakevdp.github.io/PythonDataScienceHandbook/03.02-data-indexing-and-selection.html)                                                                                                   | [Introduction](https://www.youtube.com/watch?v=fET6zb5tkro) [Warmup](https://www.youtube.com/watch?v=zB2bDqASq2s) [Workout](https://www.youtube.com/watch?v=Pm-S5rNXzu4&t=560s)                                                          |
| 16  |                               | Operating on data in Pandas             | [PDSH.3.3](https://jakevdp.github.io/PythonDataScienceHandbook/03.03-operations-in-pandas.html)                                                                                                          | [Introduction](https://www.youtube.com/watch?v=2TjSn4mmQy8) [Warmup](https://www.youtube.com/watch?v=F1lmnCwdnUU) [Workout](https://www.youtube.com/watch?v=A8tdTR7BX8w&t=2s)                                                            |
| 17  |                               | Handling missing data                   | [PDSH.3.4](https://jakevdp.github.io/PythonDataScienceHandbook/03.04-missing-values.html)                                                                                                                | [Introduction](https://www.youtube.com/watch?v=7DgLaftr-_E) [Warmup](https://www.youtube.com/watch?v=8pbIjN8nn34) [Workout](https://www.youtube.com/watch?v=frVzn-fhyS4)                                                                 |
| 18  |                               | Hierarchical indexing                   | [PDSH.3.5](https://jakevdp.github.io/PythonDataScienceHandbook/03.05-hierarchical-indexing.html)                                                                                                         | [Introduction](https://www.youtube.com/watch?v=fGyFUOgFSjI) [Warmup](https://www.youtube.com/watch?v=r0LptptZxh0) [Workout](https://www.youtube.com/watch?v=jyoBpCnaT-E&t=4s)                                                            |
| 19  | Data transformation           | Combining datasets: concat & append     | [PDSH.3.6](https://jakevdp.github.io/PythonDataScienceHandbook/03.06-concat-and-append.html)                                                                                                             | [Introduction](https://www.youtube.com/watch?v=GrpKO81ee00) [Warmup](https://www.youtube.com/watch?v=0QMgYcrdPuc) [Workout](https://www.youtube.com/watch?v=Esuwqk6akxc)                                                                 |
| 20  |                               | Combining datasets: merge & join        | [PDSH.3.7](https://jakevdp.github.io/PythonDataScienceHandbook/03.07-merge-and-join.html)                                                                                                                | [Introduction](https://www.youtube.com/watch?v=zEXOOA7VXWE) [Warmup](https://www.youtube.com/watch?v=-wQC3QUyTvI) [Workout](https://www.youtube.com/watch?v=D4oKY73OuUU)                                                                 |
| 21  |                               | Aggregation and grouping                | [PDSH.3.8](https://jakevdp.github.io/PythonDataScienceHandbook/03.08-aggregation-and-grouping.html)                                                                                                      | [Introduction](https://www.youtube.com/watch?v=CMDJ7CTu9YQ) [Warmup](https://www.youtube.com/watch?v=vihbkzhYz5Y) [Workout](https://www.youtube.com/watch?v=jWfgCWcICAc)                                                                 |
| 22  |                               | Vectorized string operations            | [PDSH.3.10](https://jakevdp.github.io/PythonDataScienceHandbook/03.10-working-with-strings.html)                                                                                                         | [Introduction](https://www.youtube.com/watch?v=nScex6aHNPA) [Warmup](https://www.youtube.com/watch?v=XC8Kk4WOMrg) [Workout](https://www.youtube.com/watch?v=ObXs5vh7u3w)                                                                 |
| 23  |                               | Working with time series                | [PDSH.3.11](https://jakevdp.github.io/PythonDataScienceHandbook/03.11-working-with-time-series.html)                                                                                                     | [Introduction](https://www.youtube.com/watch?v=Ek9Q1T9HBTc) [Warmup](https://www.youtube.com/watch?v=9LWEMs9ed34) [Workout](https://www.youtube.com/watch?v=bkjMMPCLCsE)                                                                 |
| 24  |                               | High performance Pandas                 | [PDSH.3.12](https://jakevdp.github.io/PythonDataScienceHandbook/03.12-performance-eval-and-query.html)                                                                                                   | TBD                                                                                                                                                                                                                                      |
| 25  |                               | Pivot tables                            | [PDSH.3.9](https://jakevdp.github.io/PythonDataScienceHandbook/03.09-pivot-tables.html)                                                                                                                  | TBD                                                                                                                                                                                                                                      |
| 26  | Data integration              | APIs: JSON, REST & GraphQL              | [WEB.1](https://realpython.com/python-requests/), [WEB.12](https://www.dataquest.io/blog/python-api-tutorial/), [WEB.13](https://www.howtographql.com/basics/1-graphql-is-the-better-rest/)              | [Introduction](https://www.youtube.com/watch?v=qF6tD0LMBeQ) [Warmup](https://www.youtube.com/watch?v=1oUwl7Wqv_o) [Workout](https://www.youtube.com/watch?v=sQJZXgcZsR8)                                                                 |
| 27  |                               | APIs: XML, XPATH & XQUERY               | [WEB.14](https://www.datacamp.com/community/tutorials/python-xml-elementtree), [WEB.15](https://www.w3schools.com/xml/xquery_intro.asp)                                                                  | [Introduction](https://www.youtube.com/watch?v=XQYZsVPPAtc) [Warmup](https://www.youtube.com/watch?v=R17k3c5aLJk) [Workout](https://www.youtube.com/watch?v=3qUv6u9eD6E)                                                                 |
| 28  |                               | HTML scraping                           | [WEB.3](https://www.dataquest.io/blog/web-scraping-tutorial-python/)                                                                                                                                     | [Introduction](https://www.youtube.com/watch?v=1N0QnYqnhuA) [Warmup](https://www.youtube.com/watch?v=8I8cqNDXwyg) [Workout 1](https://www.youtube.com/watch?v=iJ1FXfD3rt4) [Workout 2](https://www.youtube.com/watch?v=TG5lNEnkiVY)      |
| 29  | Data visualization            | Principles of data visualization        | [JOUR.2](https://www.researchgate.net/publication/316605154_Data_Visualization_Data_Interpreters_and_Storytelling), [WEB.4](https://www.cs.ubc.ca/~tmm/courses/531-16/lectures/lect1.pdf)                | [Introduction](https://www.youtube.com/watch?v=I2XCxY8eWCM) [How to Think about Data Visualization](https://youtu.be/vTingdk_pVM) [200 Countries, 200 Years, 4 Minutes](https://youtu.be/jbkSRLYSojo)                                    |
| 30  |                               | Introduction to Altair                  | [VISU.1](https://nbviewer.jupyter.org/github/uwdata/visualization-curriculum/blob/master/altair_introduction.ipynb)                                                                                      | [Introduction](https://www.youtube.com/watch?v=s0vgc3GpN3o) [Warmup](https://www.youtube.com/watch?v=oOC13QqUM58) [Workout](https://www.youtube.com/watch?v=SH7nWj5-J0U)                                                                 |
| 31  |                               | Types, marks, and encoding channels     | [VISU.2](https://nbviewer.jupyter.org/github/uwdata/visualization-curriculum/blob/master/altair_marks_encoding.ipynb)                                                                                    | [Introduction](https://www.youtube.com/watch?v=9y46VuJGG0A) [Warmup](https://www.youtube.com/watch?v=uUty7ePtsZg) [Workout](https://www.youtube.com/watch?v=lcbgkpWGVV8)                                                                 |
| 32  |                               | Altair data transformation              | [VISU.3](https://nbviewer.jupyter.org/github/uwdata/visualization-curriculum/blob/master/altair_data_transformation.ipynb)                                                                               | [Introduction](https://www.youtube.com/watch?v=4yG7Nka9hA4) [Warmup](https://www.youtube.com/watch?v=TGc4iiHgfWU) [Workout](https://www.youtube.com/watch?v=0O82mLIueZU)                                                                 |
| 33  |                               | Scales, axes, and legends               | [VISU.4](https://nbviewer.jupyter.org/github/uwdata/visualization-curriculum/blob/master/altair_scales_axes_legends.ipynb)                                                                               | TBD                                                                                                                                                                                                                                      |
| 34  |                               | Multi-view composition                  | [VISU.5](https://nbviewer.jupyter.org/github/uwdata/visualization-curriculum/blob/master/altair_view_composition.ipynb)                                                                                  | TBD                                                                                                                                                                                                                                      |
| 35  |                               | Interaction                             | [VISU.6](https://nbviewer.jupyter.org/github/uwdata/visualization-curriculum/blob/master/altair_interaction.ipynb)                                                                                       | TBD                                                                                                                                                                                                                                      |
| 36  | Text analytics                | Syntax: tokenization and POS tagging    | [WEB.9](http://rwet.decontextualize.com/book/textblob/)                                                                                                                                                  | [Introduction 1](https://www.youtube.com/watch?v=L0Ym4Ezw7ew) [Introduction 2](https://www.youtube.com/watch?v=ZtVODUxnPQk) [Warmup](https://www.youtube.com/watch?v=sijZV47d4bA) [Workout](https://www.youtube.com/watch?v=mMWcsCBgRwk) |
| 37  |                               | Semantics: sentiment and named entities | [WEB.11](https://spacy.io/usage/spacy-101)                                                                                                                                                               | [Introduction](https://www.youtube.com/watch?v=zGksSQmnQRE) [Warmup](https://www.youtube.com/watch?v=eQweC3Xnr3M) [Workout](https://www.youtube.com/watch?v=RnLg4RS_q-s)                                                                 |
| 38  | Network analytics             | Basic network concepts                  | [NETS.1](http://networksciencebook.com/chapter/1)                                                                                                                                                        | [Introduction 1](http://www.youtube.com/watch?v=3bBkZbqzyY4) [Introduction 2](https://www.youtube.com/watch?v=rENZi7RSsig) [Warmup](https://www.youtube.com/watch?v=RKcHT_j_F8Q) [Workout](https://www.youtube.com/watch?v=QP4IJM_DSVw)  |
| 39  |                               | Network structure                       | [NETS.2](http://networksciencebook.com/chapter/2)                                                                                                                                                        | [Introduction 1](https://www.youtube.com/watch?v=89mxOdwPfxA) [Introduction 2](https://www.youtube.com/watch?v=os5LCjd5p50) [Warmup](https://www.youtube.com/watch?v=4AVDiyyJnIM) [Workout](https://www.youtube.com/watch?v=K7jsqM5eFZA) |
| 40  |                               | Network content and structure           | [WEB.10](https://programminghistorian.org/en/lessons/exploring-and-analyzing-network-data-with-python)                                                                                                   | [Introduction 1](https://www.youtube.com/watch?v=ToXmHrKW3JY) [Introduction 2](https://www.youtube.com/watch?v=Wusro1P5NF0) [Warmup](https://www.youtube.com/watch?v=VjU6bTRj1oA) [Workout](https://www.youtube.com/watch?v=xD7MRwu8G_I) |
| 41  | Machine learning              | Introduction to machine learning        | [PDSH.5.1](https://jakevdp.github.io/PythonDataScienceHandbook/05.01-what-is-machine-learning.html), [PDSH.5.2](https://jakevdp.github.io/PythonDataScienceHandbook/05.02-introducing-scikit-learn.html) | [Introduction](https://www.youtube.com/watch?v=sJvITsBu0Gc) [Warmup](https://www.youtube.com/watch?v=7JiBiayZh90) [Workout](https://www.youtube.com/watch?v=Bq8z2wEtgWQ)                                                                 |
| 42  |                               | Linear regression                       | [PDSH.5.6](https://jakevdp.github.io/PythonDataScienceHandbook/05.06-linear-regression.html)                                                                                                             | [Introduction](https://www.youtube.com/watch?v=Zbmdtx1r8Xg) [Warmup](https://www.youtube.com/watch?v=w8o5xTxdGFo) [Workout](https://www.youtube.com/watch?v=cpWQuzga5po)                                                                 |
| 43  |                               | Decision trees                          | [PDSH.5.8](https://jakevdp.github.io/PythonDataScienceHandbook/05.08-random-forests.html)                                                                                                                | [Introduction](https://www.youtube.com/watch?v=AxVXn3mroU8) [Warmup](https://www.youtube.com/watch?v=TvAVaq25u5Q) [Workout](https://www.youtube.com/watch?v=eGMaiJLpM94)                                                                 |
| 44  |                               | Clustering                              | [PDSH.5.11](https://jakevdp.github.io/PythonDataScienceHandbook/05.11-k-means.html)                                                                                                                      | [Introduction](https://www.youtube.com/watch?v=_do72LGE27Q) [Warmup](https://www.youtube.com/watch?v=PLXnejUyoec) [Workout](https://www.youtube.com/watch?v=0AHA4IHkuaE)                                                                 |
| 45  |                               | Course wrap-up                          | [JOUR.3](https://hbr.org/2012/10/data-scientist-the-sexiest-job-of-the-21st-century)                                                                                                                     | [Course Wrap-Up](https://www.youtube.com/watch?v=irkyD4mBzNk)                                                                                                                                                                            |

## Source Code

## Software
Python 3.7 or higher is required. The easy way to install it is with [Anaconda distribution](https://www.anaconda.com/download). Several other packages including Pandas, Altair and Scikit-learn are needed among others. A `requirements.txt` is 
provided. All required packages can be installed with `pip install -r requirements.txt`

## Readings
This courses uses open access materials. I appreciate and thank authors and publishers
who made these resources free to use.

The numbers on the lists below match those in the table.

- WTOP: [A Whirlwind Tour of Python](https://jakevdp.github.io/WhirlwindTourOfPython/): a fast-paced introduction to essential features of the Python language.
  - 1 [Introduction](http://nbviewer.jupyter.org/github/jakevdp/WhirlwindTourOfPython/blob/master/00-Introduction.ipynb)
  - 2 [How to Run Python Code](http://nbviewer.jupyter.org/github/jakevdp/WhirlwindTourOfPython/blob/master/01-How-to-Run-Python-Code.ipynb)
  - 3 [Basic Python Syntax](http://nbviewer.jupyter.org/github/jakevdp/WhirlwindTourOfPython/blob/master/02-Basic-Python-Syntax.ipynb)
  - 4 [Python Semantics: Variables](http://nbviewer.jupyter.org/github/jakevdp/WhirlwindTourOfPython/blob/master/03-Semantics-Variables.ipynb)
  - 5 [Python Semantics: Operators](http://nbviewer.jupyter.org/github/jakevdp/WhirlwindTourOfPython/blob/master/04-Semantics-Operators.ipynb)
  - 6 [Built-In Scalar Types](http://nbviewer.jupyter.org/github/jakevdp/WhirlwindTourOfPython/blob/master/05-Built-in-Scalar-Types.ipynb)
  - 7 [Built-In Data Structures](http://nbviewer.jupyter.org/github/jakevdp/WhirlwindTourOfPython/blob/master/06-Built-in-Data-Structures.ipynb)
  - 8 [Control Flow Statements](http://nbviewer.jupyter.org/github/jakevdp/WhirlwindTourOfPython/blob/master/07-Control-Flow-Statements.ipynb)
  - 9 [Defining Functions](http://nbviewer.jupyter.org/github/jakevdp/WhirlwindTourOfPython/blob/master/08-Defining-Functions.ipynb)
  - 10 [Errors and Exceptions](http://nbviewer.jupyter.org/github/jakevdp/WhirlwindTourOfPython/blob/master/09-Errors-and-Exceptions.ipynb)
  - 11 [Iterators](http://nbviewer.jupyter.org/github/jakevdp/WhirlwindTourOfPython/blob/master/10-Iterators.ipynb)
  - 12 [List Comprehensions](http://nbviewer.jupyter.org/github/jakevdp/WhirlwindTourOfPython/blob/master/11-List-Comprehensions.ipynb)
  - 13 [Generators and Generator Expressions](http://nbviewer.jupyter.org/github/jakevdp/WhirlwindTourOfPython/blob/master/12-Generators.ipynb)
  - 14 [Modules and Packages](http://nbviewer.jupyter.org/github/jakevdp/WhirlwindTourOfPython/blob/master/13-Modules-and-Packages.ipynb)
  - 15 [Strings and Regular Expressions](http://nbviewer.jupyter.org/github/jakevdp/WhirlwindTourOfPython/blob/master/14-Strings-and-Regular-Expressions.ipynb)

- PDSH: [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook): a complete coverage for modern Python tools for researchers and data scientists.
  - 3 [Data Manipulation with Pandas](https://nbviewer.jupyter.org/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/03.00-Introduction-to-Pandas.ipynb)
    - 1 [Introducing Pandas Objects](https://nbviewer.jupyter.org/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/03.01-Introducing-Pandas-Objects.ipynb)
    - 2 [Data Indexing and Selection](https://nbviewer.jupyter.org/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/03.02-Data-Indexing-and-Selection.ipynb)
    - 3 [Operating on Data in Pandas](https://nbviewer.jupyter.org/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/03.03-Operations-in-Pandas.ipynb)
    - 4 [Handling Missing Data](https://nbviewer.jupyter.org/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/03.04-Missing-Values.ipynb)
    - 5 [Hierarchical Indexing](https://nbviewer.jupyter.org/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/03.05-Hierarchical-Indexing.ipynb)
    - 6 [Combining Datasets: Concat and Append](https://nbviewer.jupyter.org/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/03.06-Concat-And-Append.ipynb)
    - 7 [Combining Datasets: Merge and Join](https://nbviewer.jupyter.org/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/03.07-Merge-and-Join.ipynb)
    - 8 [Aggregation and Grouping](https://nbviewer.jupyter.org/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/03.08-Aggregation-and-Grouping.ipynb)
    - 9 [Pivot Tables](https://nbviewer.jupyter.org/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/03.09-Pivot-Tables.ipynb)
    - 10 [Vectorized String Operations](https://nbviewer.jupyter.org/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/03.10-Working-With-Strings.ipynb)
    - 11 [Working with Time Series](https://nbviewer.jupyter.org/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/03.11-Working-with-Time-Series.ipynb)
    - 12 [High-Performance Pandas: eval() and query()](https://nbviewer.jupyter.org/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/03.12-Performance-Eval-and-Query.ipynb)
  - 5 [Machine Learning](https://nbviewer.jupyter.org/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/05.00-Machine-Learning.ipynb)
    - 1 [What Is Machine Learning?](https://nbviewer.jupyter.org/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/05.01-What-Is-Machine-Learning.ipynb)
    - 2 [Introducing Scikit-Learn](https://nbviewer.jupyter.org/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/05.02-Introducing-Scikit-Learn.ipynb)
    - 3 [Hyperparameters and Model Validation](https://nbviewer.jupyter.org/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/05.03-Hyperparameters-and-Model-Validation.ipynb)
    - 4 [Feature Engineering](https://nbviewer.jupyter.org/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/05.04-Feature-Engineering.ipynb)
    - 5 [In Depth: Naive Bayes Classification](https://nbviewer.jupyter.org/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/05.05-Naive-Bayes.ipynb)
    - 6 [In Depth: Linear Regression](https://nbviewer.jupyter.org/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/05.06-Linear-Regression.ipynb)
    - 7 [In-Depth: Support Vector Machines](https://nbviewer.jupyter.org/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/05.07-Support-Vector-Machines.ipynb)
    - 8 [In-Depth: Decision Trees and Random Forests](https://nbviewer.jupyter.org/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/05.08-Random-Forests.ipynb)
    - 9 [In Depth: Principal Component Analysis](https://nbviewer.jupyter.org/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/05.09-Principal-Component-Analysis.ipynb)
    - 10 [In-Depth: Manifold Learning](https://nbviewer.jupyter.org/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/05.10-Manifold-Learning.ipynb)
    - 11 [In Depth: k-Means Clustering](https://nbviewer.jupyter.org/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/05.11-K-Means.ipynb)

- VISU: [Data Visualization Curriculum](https://github.com/uwdata/visualization-curriculum): a data visualization curriculum of interactive notebooks from UW Interactive Data Lab.
  - 1 [Introduction to Vega-Lite / Altair](https://colab.research.google.com/github/uwdata/visualization-curriculum/blob/master/altair_introduction.ipynb)
  - 2 [Data Types, Graphical Marks, and Visual Encoding Channels](https://colab.research.google.com/github/uwdata/visualization-curriculum/blob/master/altair_marks_encoding.ipynb)
  - 3 [Data Transformation](https://colab.research.google.com/github/uwdata/visualization-curriculum/blob/master/altair_data_transformation.ipynb)
  - 4 [Scales, Axes, and Legends](https://colab.research.google.com/github/uwdata/visualization-curriculum/blob/master/altair_scales_axes_legends.ipynb)
  - 5 [Multi-View Composition](https://colab.research.google.com/github/uwdata/visualization-curriculum/blob/master/altair_view_composition.ipynb)
  - 6 [Interaction](https://github.com/uwdata/visualization-curriculum/blob/master/altair_interaction.ipynb)
  - 7 [Cartographic Visualization](https://colab.research.google.com/github/uwdata/visualization-curriculum/blob/master/altair_cartographic.ipynb)

- NETS: [Network Science](http://networksciencebook.com/): a freely available textbook for network science by Albert-László Barabási and others
  - 1:[Network Science Book: Chapter 1](http://networksciencebook.com/chapter/1)
  - 2:[Network Science Book: Chapter 2](http://networksciencebook.com/chapter/2)

- Articles from the web
  - WEB.0: [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
  - WEB.1: [Python’s Requests Library (Guide)](https://realpython.com/python-requests/)
  - WEB.2: [Quandl API Documentation](https://docs.quandl.com)
  - WEB.3: [Python Web Scraping Using BeautifulSoup](https://www.dataquest.io/blog/web-scraping-tutorial-python/)
  - WEB.4: [Intro, Data and Tasks, Marks and Channels](https://www.cs.ubc.ca/~tmm/courses/531-16/lectures/lect1.pdf)
  - WEB.5: [Visualizing statistical relationships](https://seaborn.pydata.org/tutorial/relational.html)
  - WEB.6: [Plotting with categorical data](https://seaborn.pydata.org/tutorial/categorical.html)
  - WEB.7: [Visualizing the distribution of a dataset](https://seaborn.pydata.org/tutorial/distributions.html)
  - WEB.8: [Text Analytics for Beginners using NLTK](https://www.datacamp.com/community/tutorials/text-analytics-beginners-nltk)
  - WEB.9: [Natural Language Basics with TextBlob](http://rwet.decontextualize.com/book/textblob/)
  - WEB.10:[Exploring and Analyzing Network Data with Python](https://programminghistorian.org/en/lessons/exploring-and-analyzing-network-data-with-python)
  - WEB.11:[spaCy 101: Everything you need to know](https://spacy.io/usage/spacy-101)
  - WEB.12: [Python API Tutorial: Getting Started with APIs](https://www.dataquest.io/blog/python-api-tutorial/)
  - WEB.13: [GraphQL is the better REST](https://www.howtographql.com/basics/1-graphql-is-the-better-rest/)
  - WEB.14: [Python XML with ElementTree: Beginner's Guide](https://www.datacamp.com/community/tutorials/python-xml-elementtree)
  - WEB.15: [XQuery Tutorial](https://www.w3schools.com/xml/xquery_intro.asp)
 
- Journal articles
  - JOUR.1: [Watson, Hugh J. "Should you pursue a career in BI/analytics." Business Intelligence Journal (2015).](https://www.academia.edu/33249922/Should_You_Pursue_a_Career_in_BI_Analytics)
  - JOUR.2: [Watson, H. "Data Visualization, Data Interpreters, and Storytelling." Business Intelligence Journal (2017)](https://www.researchgate.net/publication/316605154_Data_Visualization_Data_Interpreters_and_Storytelling)
  - JOUR.3: [Davenport, T. H., & Patil, D. J. "Data Scientist: The Sexiest Job of the 21st Century." Harvard business review (2012)](https://hbr.org/2012/10/data-scientist-the-sexiest-job-of-the-21st-century)
 
