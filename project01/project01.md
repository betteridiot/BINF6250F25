Project01
================
Marcus D Sherman
2025-09-08

- [Using RMarkdown as intended to create basic R
  references.](#using-rmarkdown-as-intended-to-create-basic-r-references)
- [Using RMarkdown to implement Python
  code](#using-rmarkdown-to-implement-python-code)
- [Using Python stuff in R and vice
  versa](#using-python-stuff-in-r-and-vice-versa)

# Using RMarkdown as intended to create basic R references.

``` r
r2py_object <- "first object"
```

# Using RMarkdown to implement Python code

``` python
py2r_object = 42
```

# Using Python stuff in R and vice versa

``` r
print(py$py2r_object)
```

    ## [1] 42

``` python
print(r.r2py_object)
```

    ## first object
