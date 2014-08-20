
# rOpenSci lightning talks

If you are attending a conference, or have a chance to speak about the rOpenSci project at your institution, this slide deck will provide you with a useful starting point to quickly build and customize your own presentation. 

__How to use this repo__

1. Fork this repo into your own account
2. Edit the slides (at the very least edit [your name and url](https://github.com/ropensci/ropensci_intro/blob/gh-pages/index.Rhtml#L3-L6) of the presentation at the top of `index.Rhtml`).
3. Remove any slides that might be irrelevant to your audience.
4. To build `index.html` run this from your shell:

```bash
make slides
# Or of you don't have Make
Rscript -e "library(knitr); knit('index.Rhtml', quiet = TRUE)"
```

This repo only has a `gh-pages` branch and no master. So once you clone, there is no need to create and push to a new `gh-pages` branch. 

Then you can present your talk at `http://YOUR_USERNAME.github.io/ropensci_intro`. This presentation, for example, is available at [`http://ropensci.github.io/ropensci_intro`](http://ropensci.github.io/ropensci_intro)

This frees you up from even bringing your own laptop if there already one at the venue. If you anticipate not having an internet connection, simply clone a copy first on to a thumbdrive before you no lose internet access.

---

[![](http://ropensci.org/public_images/github_footer.png)](http://ropensci.org)

