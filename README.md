# r-pkg-slides

<!-- badges: start -->
[![Blog post](https://img.shields.io/badge/rostrum.blog-post-008900?labelColor=000000&logo=data%3Aimage%2Fgif%3Bbase64%2CR0lGODlhEAAQAPEAAAAAABWCBAAAAAAAACH5BAlkAAIAIf8LTkVUU0NBUEUyLjADAQAAACwAAAAAEAAQAAAC55QkISIiEoQQQgghRBBCiCAIgiAIgiAIQiAIgSAIgiAIQiAIgRAEQiAQBAQCgUAQEAQEgYAgIAgIBAKBQBAQCAKBQEAgCAgEAoFAIAgEBAKBIBAQCAQCgUAgEAgCgUBAICAgICAgIBAgEBAgEBAgEBAgECAgICAgECAQIBAQIBAgECAgICAgICAgECAQECAQICAgICAgICAgEBAgEBAgEBAgICAgICAgECAQIBAQIBAgECAgICAgIBAgECAQECAQIBAgICAgIBAgIBAgEBAgECAgECAgICAgICAgECAgECAgQIAAAQIKAAAh%2BQQJZAACACwAAAAAEAAQAAAC55QkIiESIoQQQgghhAhCBCEIgiAIgiAIQiAIgSAIgiAIQiAIgRAEQiAQBAQCgUAQEAQEgYAgIAgIBAKBQBAQCAKBQEAgCAgEAoFAIAgEBAKBIBAQCAQCgUAgEAgCgUBAICAgICAgIBAgEBAgEBAgEBAgECAgICAgECAQIBAQIBAgECAgICAgICAgECAQECAQICAgICAgICAgEBAgEBAgEBAgICAgICAgECAQIBAQIBAgECAgICAgIBAgECAQECAQIBAgICAgIBAgIBAgEBAgECAgECAgICAgICAgECAgECAgQIAAAQIKAAA7)](https://www.rostrum.blog/2019/11/01/usethis/)
<!-- badges: end -->

## What?

This is a fork of the phenomenal R repo `r-pkg-slides` written by [Matt Dray](https://github.com/matt-dray/r-pkg-slides), which I've tweaked slightly for the Bergen R Ladies "How to make an R package" workshop in August 2022. The changes include updates for 2022 {usethis} usage and a change from cats to fjords. The slideshow provides nice clear instructions on how to build your very first R package. 

This repo contains code to create the slides themselves, built using the [xaringan](https://github.com/yihui/xaringan) package. Think of it like Markdown-but-for-slides.

## The topic

The talk is about how to make an R package easily, with help from the {usethis} package in particular.

You can:

* [see the slides in your browser](https://popovs.github.io/r-pkg-slides/)
* explore the source code for the slides in this repo
* [read the accompanying original blog post](https://www.rostrum.blog/2019/11/01/usethis/)

## The package

In the session we'll live-build a package called {fjoRds} and push it to GitHub. You'll be able to:

* look at the source code
* see the package's website, made with {pkgdown}
* install the package with `remotes::install_github("popovs/fjoRds")`
* run the `fjord_finder()` function to find out if a supplied character string matches the name of a [Norwegian fjord](https://en.wikipedia.org/wiki/List_of_Norwegian_fjords)


