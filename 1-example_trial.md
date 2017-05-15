The code below demonstrates two color palettes in the [viridis](https://github.com/sjmgarnier/viridis) package. Each plot displays a contour map of the Maunga Whau volcano in Auckland, New Zealand.

Viridis colors
--------------

``` r
image(volcano, col = viridis(200))
```

![](1-example_trial_files/figure-markdown_github/unnamed-chunk-2-1.png)

Magma colors
------------

``` r
image(volcano, col = viridis(200, option = "A"))
```

![](1-example_trial_files/figure-markdown_github/unnamed-chunk-3-1.png)
