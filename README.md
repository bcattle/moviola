moviola
=======

A modern distributed thumbnail generation and image-processing framework

System overview
-------------------

![Diagram of code structure](../master/doc/system.png)


### Modules

### Fetchers

`http()`

### Plugins

#### Resize

`resize()`

#### Crop

`crop()`

#### Grayscale

`gray()`

#### Face detection

`facedetect()`

#### Compositing

`composite()`

#### Perceptual hash

`hash()`

### Backing store

`store()`

### URL cache

### Frontend

`return()`

#### REST interface

URL examples:

Connect the above commans with a syntax similar to UNIX pipes:

`/ola/?http(img.youtube.com/vi/idzgD10APUE/maxresdefault.jpg) | resize(0.5) | store() | return(base64)`
