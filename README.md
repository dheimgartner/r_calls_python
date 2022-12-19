# R <3 python

Very minimal example of how to use R and python functions in a R package.

> Please read reticulates vignette of how to use python functionality in R properly (e.g. when importing modules, `.onLoad` stuff and other things.

Test like so:

```
devtools::install_github("dheimgartner/r_calls_python")
trump <- r_calls_python::python_import_module("trump")
trump$make()
trump$great()
```
