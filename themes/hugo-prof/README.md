# Hugo Prof

A clean, simple theme designed for academics for [Hugo](https://gohugo.io/).  It is derived from https://github.com/yihui/hugo-lithium (in turn forked from https://github.com/jrutheiser/hugo-lithium-theme with modifications to make it work better with [**blogdown**](https://github.com/rstudio/blogdown) with a sidebar derived from [Skeleton](https://github.com/dhg/Skeleton/tree/master).

The easiest way to get started is to create a new (empty) RStudio project, then

```r
devtools::install_github('rstudio/blogdown')  # install blogdown
blogdown::new_site(theme = 'fsolt/hugo-prof')
```

Then you should be able to see an example website launched in the RStudio Viewer.

For the full documentation, please see this section in the **blogdown** book: https://bookdown.org/yihui/blogdown/themes.html

## Features

- Blog
- Responsive
- Disqus
- Google Analytics
- Google web fonts (Merriweather and Lato)
- MathJax
- highlight.js

## License

The original hugo-lithium-theme was released by Jonathan Rutheiser under [the MIT License](https://github.com/jrutheiser/hugo-lithium-theme/blob/master/LICENSE.md). The modified version released [by Yihui Xie](https://github.com/yihui/hugo-lithium/blob/master/LICENSE.md) was also released under MIT, as was [Dave Gamache's Skeleton](https://github.com/dhg/Skeleton/blob/master/LICENSE.md).  Building on all of these, and consistent with their licenses, `hugo-prof` is released under the MIT Licence as well.
