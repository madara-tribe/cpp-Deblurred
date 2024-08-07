# Deblure image through cpp


# test run
```
# compile
$ g++ -std=c++11 mask2color.cpp -o mask2color `pkg-config --cflags opencv` `pkg-config --libs opencv`
# test run
$ ./mask2color
```

# Deblurred image
```
# compile
$ g++ -std=c++11 deblur.cpp -o deblur `pkg-config --cflags opencv` `pkg-config --libs opencv`
# deblurred
$ ./deblur
```


## result
<b>・original/deblurred</b>

<img src="https://github.com/user-attachments/assets/b32fcd19-fc5f-4f7f-bb44-19203ed107d5" width="400px" height="300px"/><img src="https://github.com/user-attachments/assets/46d6d932-9458-4c9f-b571-de7ba31a0606" width="400px" height="300px"/>


# References
・[opencv:Out-of-focus Deblur Filter](https://docs.opencv.org/4.x/de/d3c/tutorial_out_of_focus_deblur_filter.html#autotoc_md765)
・[image- deblurred](https://github.com/navyajain16/Image-Deblurring)
・[psf2otf](https://github.com/aboucaud/pypher/blob/master/pypher/pypher.py)

