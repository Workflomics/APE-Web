# APE Web

[![Latest release](https://img.shields.io/github/release/workflomics/APE-Web.svg)](https://github.com/workflomics/APE-Web/releases/latest)
[![Build Status](https://www.travis-ci.com/workflomics/APE-Web.svg?branch=master)](https://www.travis-ci.com/workflomics/APE-Web)
[![Build](https://github.com/workflomics/APE-web/actions/workflows/build.yml/badge.svg)](https://github.com/workflomics/APE-web/actions/workflows/build.yml)
[![GitHub license](https://img.shields.io/github/license/workflomics/APE-Web)](https://github.com/workflomics/APE-Web/blob/master/LICENSE)
[![DOI](https://zenodo.org/badge/360515462.svg)](https://zenodo.org/badge/latestdoi/360515462)

[APE](https://github.com/sanctuuary/APE) is a command line tool and Java API for the automated exploration of possible computational pipelines (scientific workflows) from large collections of computational tools.

This project is APE Web, the web interface for APE.
It consists of a separate front-end and back-end, which can be found in their own respective directories.
For details regarding the front-end and back-end specifically, please see their README files.

APE Web is hosted at https://ape.science.uu.nl/ 

A short video that explains the platform is available at:
<div align="left">
  <a href="https://www.youtube.com/watch?v=_dLJeBs5iUU" target="_blank"><img src="https://user-images.githubusercontent.com/11068408/123432265-7c45ee80-d5ca-11eb-886d-06309e8ecdb8.png" alt="APE - Youtube video" width=30%></a>
</div>

## Requirements

To run APE Web, the front-end requires [Node.js](https://nodejs.org) and the back-end requires [Java](https://www.oracle.com/java/technologies/javase-downloads.html#JDK11).
Full details can be found in their own respective README files.

The full project can also be run using Docker Compose.
See the docker-compose.yml file for a basic setup.

## Using APE Web

A running instance of APE Web can be found [here](https://ape.science.uu.nl).
It is set up with different use cases from the [APE Use Cases Repository](https://github.com/sanctuuary/APE_UseCases).

### Using Docker

Please follow the configuration instructions in the [front-end](https://github.com/sanctuuary/APE-Web/blob/master/front-end/README.md)
and [back-end](https://github.com/sanctuuary/APE-Web/blob/master/back-end/README.md) README files first.
After configuring, APE Web can be easily deployed using Docker Compose, simply by running:
```shell
docker-compose up -d
```
An initial admin account on the website can be created using the instructions in `scripts/README.md`.

If you wish to change the configuration of the front-end and/or back-end first, please read their README's for instructions.

## The APE Web team

This project was initially developed by students from the bachelor Computer Science at Utrecht University within the Software Project course, and students from Grafisch Lyceum Utrecht.
* Silvan Eelman
* Koen Haverkort
* Alex Janse
* Matthijs Rademaker
* Megan Tjoeng
* Inge van Dam
* Jeroen van der Wal
* Sem van Nieuwenhuizen
* Rens Wolters
* Sarrisa Wouts

Currently, it is being maintained by:
* Vedran Kasalica (v.kasalica[at]uu.nl), lead developer
* Koen Haverkort, student developer
* Anna-Lena Lamprecht (a.l.lamprecht[at]uu.nl), project initiator and principal investigator

## Contact

For any questions concerning APE please get in touch with Vedran Kasalica (v.kasalica[at]uu.nl).

## Contributions

We welcome contributions (bug reports, bug fixes, feature requests, extensions, use cases, ...) to APE.
Please get in touch with Vedran Kasalica (v.kasalica@uu.nl) to coordinate your contribution.
We expect all contributors to follow our Code of Conduct.

## License

APE Web is licensed under the Apache 2.0 license.
