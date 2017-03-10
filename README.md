# mingrisch.github.io-src

Setting up a pelican-based blog, which is served via github pages. The purpose is to publish various notebooks, preferably jupyter and Rmd.

Herein, I closely follow https://github.com/jakevdp/jakevdp.github.io-source. 
First, I create a conda environment and install some packages (working wiht anaconda python).

```
$ conda create -n pelican-blog python=3.5 jupyter notebook         
$ source activate pelican-blog
$ pip install pelican Markdown ghp-import
```

