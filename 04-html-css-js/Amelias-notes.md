Amelia's notes
================
Amelia McNamara
4/14/2019

Yihui said he wasn't going to use slides, but do some live-coding. I decided to take some notes here and commit them to the day 0 repo so they would be available.

Usually, I would make an html file using SublimeText2, but Yihui showed a way to use an R function to create and open a new HTML document!

``` r
file.edit("test.html")
```

You can serve the file using the `servr` package.

``` r
servr::httw()
```

If you navigate to `test.html` in your Viewer, you can add code to the file, save, and see it immediately reflected in the served version.

We started with a text file, which didn't have any tags. But now we're going to start making it more like a real HTML file.

We're adding HTML tags into `index.html`. RStudio actually does tag matching! So cool.

Almost every time you start a tag, like `<html>`, you need to close it with a slash version, `</html>`. This is not true for `<src>`, though.

One magic thing
---------------

[Greg Wilson](http://third-bit.com/10rules/) has a quote, "…and that ninety percent of magic consists of knowing one extra thing."

One magic thing is to right-click on any web page and select "View Source."

Another magic thing
-------------------

You can also right-click on an element and select "Inspect" to see how any element on a page has been generated.
