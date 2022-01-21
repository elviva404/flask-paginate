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