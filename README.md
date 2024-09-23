
<!-- README.md is generated from README.Rmd. Please edit that file -->

# GeoLocatoR 🕊️📦 <a href="https://github.com/rafnuss/geolocator"><img src="man/figures/logo.png" align="right" height="139" alt="GeoLocatoR website" /></a>

<!-- badges: start -->

[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
[![R-CMD-check](https://github.com/Rafnuss/GeoLocatoR/workflows/R-CMD-check/badge.svg)](https://github.com/Rafnuss/GeoLocatoR/actions)
[![lint](https://github.com/Rafnuss/GeoPressureR/actions/workflows/lint.yaml/badge.svg)](https://github.com/Rafnuss/GeoPressureR/actions/workflows/lint.yaml)
<!-- badges: end -->

**GeoLocatoR** is here to help you fly through the complexities of
geolocator data management with ease! This package will facilitate the
creation, use, and sharing of your geolocator data like never before.

## 🚀 Overview

GeoLocatoR is designed to help you create and work with the
[**GeoLocator Data Package (GeoLocator
DP)**](https://raphaelnussbaumer.com/GeoLocator-DP/), a standardized
format for geolocator data that follows the [Data Package
standard](https://datapackage.org/standard/data-package/). No more
flapping around with messy data structures—GeoLocatoR ensures that your
data is organized, accessible, and ready to share with the world.

## 🦅 Main Features

- **Create a Geolocator Data Package**: Easily create a geolocator
  datapackage object, add resources (data), and write the data package
  to your preferred directory. Or, read an existing data package from a
  directory or from Zenodo like a pro.
- **Works Seamlessly with GeoPressureTemplate**: GeoLocatoR is perfectly
  tailored to work with
  [GeoPressureTemplate](https://github.com/Rafnuss/GeoPressureTemplate)—a
  template repository for analyzing geolocator data using GeoPressureR.
  Use this dynamic duo to streamline your analysis, maintain a
  standardized project structure, and keep your geolocator data in
  perfect formation. (See vignette: *Create from GeoPressureTemplate*)
- **Supports Swiss Ornithological Institute Data**: GeoLocatoR also
  plays nicely with data from the Swiss Ornithological Institute. No
  more manual wrangling—just let GeoLocatoR do the heavy lifting! (See
  vignette: *Create from SOI*)
- **Built on frictionless-r**: This package is built on top of the
  `frictionless-r` package, adhering to the Frictionless Data standards
  for open data. Think of it as the wind beneath GeoLocatoR’s wings!

## 📦 What is a Data Package?

A **Data Package** is a lightweight format for packaging data using the
[Data Package standard](https://datapackage.org/standard/data-package/).
It provides a framework for organizing your data files, metadata, and
descriptive information in a consistent and reusable manner. For
geolocator data, this ensures that information about tagged birds, their
movements, and associated metadata are all neatly bundled into one
easily exchangeable package.

GeoLocatoR takes this standard and applies it to the ornithological
realm, enabling you to structure your geolocator data effectively. Learn
more about the GeoLocator DP standard
[here](https://raphaelnussbaumer.com/GeoLocator-DP/).

## 🛠️ Installation

You can install GeoLocatoR from GitHub:

``` r
# install.packages("pak")
pak::pkg_install("Rafnuss/GeoLocatoR")
```

## 📖 Usage

GeoLocatoR makes it easy to work with your geolocator data. Here’s a
quick example:

For more detailed examples and use cases, check out the vignettes: -
[Create from
GeoPressureTemplate](vignettes/Create_from_GeoPressureTemplate.html) -
[Create from SOI](vignettes/Create_from_SOI.html)

## 📚 Citation

If you use GeoLocatoR in your research, please cite it as follows:

> Nussbaumer, R. (2021). GeoLocatoR: A package for managing geolocator
> data. R package version 0.1.0.
