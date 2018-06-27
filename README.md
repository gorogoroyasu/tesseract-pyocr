#Dockerfile to use pyocr based on tesseract

This Dockerfile is to create an Docker Image containing the list below

version of tesseract
```
root@container-id:/# tesseract --version
tesseract 3.04.01
 leptonica-1.73
  libgif 5.1.2 : libjpeg 8d (libjpeg-turbo 1.4.2) : libpng 1.2.54 : libtiff 4.0.6 : zlib 1.2.8 : libwebp 0.4.4 : libopenjp2 2.1.0

```

additional libraries
```
root@container-id:/# conda -V
conda 4.5.4

root@container-id:/# pip freeze | grep pyocr
pyocr==0.5.1
```
