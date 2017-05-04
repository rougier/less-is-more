### Less is More

![](./less-is-more.gif)

A remake of the
[Less is More](http://www.darkhorseanalytics.com/blog/data-looks-better-naked)
animation by Darkhorse Analytics, using Matplotlib 2.0.

```
$ for i in `seq 1 35`; do echo $i; python less-is-more.py $i; done
$ cp frame-35.png frame-36.png
$ cp frame-35.png frame-37.png
$ cp frame-35.png frame-38.png
$ cp frame-35.png frame-39.png
$ cp frame-35.png frame-40.png
$ convert -delay 100 *.png less-is-more.gif
```
