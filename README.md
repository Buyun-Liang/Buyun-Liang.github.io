## Download

You need to download `./jemdoc`,`./www/main.css`, `./www/table.css` and `./jemdoc_files/mysite.conf` files.

Notice that, **you have to download the `./jemdoc` excutable, because there were some modification from the original one in [`jemdox+Mathjax`](https://szl2.github.io/jemdoc-new-design/www/index.html)**.

The usage is exactly the same as [`jemdoc`](https://jemdoc.jaboc.net/). Refer [this page](https://jemdoc.jaboc.net/) for how to jemdoc.

## Usage

Assuming you have already install the  `jemdoc+MathJax`, notice that

in `./jemdoc_files/`, we store `.jemdoc` files and `mysite.conf`

in `./www/`, we store the output `.html` / `.css` / `.js` files and website assets.

Suppose you are currently in `./jemdoc_files/`, we use the following to compile

```
python ../jemdoc -c mysite.conf -o ../www/  *.jemdoc
```

You can also use this for single page generation or all page generation by using `*.jemdoc`.
