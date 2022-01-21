flask-paginate
==============

Pagination support for flask framework (study from will_paginate).
It supports several css frameworks.
It requires Python2.6+ as string.format syntax.

If you want to show pagination-info
("Total <b>100</b> posts, displaying <b>20 - 30</b>")
above the pagination links,
please add the below lines to your css file::

.. sourcecode:: css

    .pagination-page-info {
        padding: .6em;
        padding-left: 0;
        width: 40em;
        margin: .5em;
        margin-left: 0;
        font-size: 12px;
    }
    .pagination-page-info b {
        color: black;
        background: #6aa6ed;
        padding-left: 2px;
        padding: .1em .25em;
        font-size: 150%;
    }

Full documentation: <http://flask-paginate.readthedocs.io>

Run example:

    $cd example
    $python sql.py
    $python sql.py init-db
    $python sql.py fill-data --total=310
    $cp app.cfg.example app.cfg
    $echo edit app.cfg
    $python app.py --port 5000

Open <http://localhost:5000> to see the example page.

![demo](/example/demo.png "demo")


# Flask-Paginate Technical Documentation

**Last updated:** 2022-01-21\
_Document generation aided by **Documatic**_

Automatic Documentation

* [Introduction](#introduction)
* [Code Overview](#code-overview)

## Introduction

This is a technical document detailing
        at a high-level
        what Flask-Paginate does, how it operates,
        and how it is built.

The outline of this document was generated
        by **Documatic**.
<!---Documatic-section-group: arch-start--->


## Project Architecture


<!---Documatic-section-group: arch-end--->

<!---Documatic-section-group: helloworld-start--->


## Code Overview

The codebase has a 2-deep folder structure, with 7 in total.
<!---Documatic-section-helloworld: setup-start--->

No exact compatable Python version has been detected.
Versions below 3.8 are compatable.


Run `pip install -e .` in top-level directory to install
package in local directory.
Install from pypi with `pip install main`.



<!---Documatic-section-helloworld: setup-end--->
`flask-paginate.example.app` has a `__main__` entrypoint, which calls:

* `flask-paginate.example.app.run`

`flask-paginate.example.sql` has a `__main__` entrypoint, which calls:

* `flask-paginate.example.sql.cli`


<!---Documatic-section-helloworld: entrypoints-start--->


## Entrypoints

There are 0 source code entrypoints in top-level `__main__`/`__init__` files.


<!---Documatic-section-helloworld: entrypoints-end--->

<!---Documatic-section-group: concept-start--->
## Concepts
<!---Documatic-section-group: concept-end--->

<!---Documatic-section-group: helloworld-end--->

<!---Documatic-section-group: dev-start--->


## Developers
<!---Documatic-section-dev: setup-start--->
* Tests are present in `tests/`




<!---Documatic-section-dev: setup-end--->

<!---Documatic-section-dev: ci-start--->
No CI/CD config files were detected.


<!---Documatic-section-dev: ci-end--->

<!---Documatic-section-group: dev-end--->

### **flask-paginate/**

#### example/

`example/` relies most on `flask_paginate/` (imports 2 times).

#### flask_paginate/

No files in `flask_paginate/` import local package files.

#### tests/

`tests/` relies most on `flask_paginate/` (imports 1 times).

#### docs/

No files in `docs/` import local package files.