# ffmpeg
ffmpeg Docker build image for Ubuntu 

# About

- FFmpeg http://ffmpeg.org
- x264 https://www.videolan.org/developers/x264.html H.264/AVC encoder
- x265 https://bitbucket.org/multicoreware/x265/wiki/Home x265 HEVC Encoder
- libvpx http://www.linuxfromscratch.org/blfs/view/svn/multimedia/libvpx.html

![pulls](https://img.shields.io/docker/pulls/sitkevij/ffmpeg.svg?style=plastic) ![stars](https://img.shields.io/docker/stars/sitkevij/ffmpeg.svg?style=plastic) ![build](https://travis-ci.org/sitkevij/ffmpeg.svg?branch=master)
# Running

The default container ENTRYPOINT is `ffmpeg`. 

To run ffmpeg from the container execute:
`docker run sitkevij/ffmpeg <ffmpeg-parameters>`

Print ffmpeg help:
`docker run sitkevij/ffmpeg --help`

Print ffmpeg version (2.8.11):
`docker run sitkevij/ffmpeg -version`

# ffmpeg -version
```
ffmpeg version 2.8.11-0ubuntu0.16.04.1 Copyright (c) 2000-2017 the FFmpeg developers
  built with gcc 5.4.0 (Ubuntu 5.4.0-6ubuntu1~16.04.4) 20160609
  configuration: --prefix=/usr --extra-version=0ubuntu0.16.04.1 --build-suffix=-ffmpeg 
--toolchain=hardened 
--libdir=/usr/lib/x86_64-linux-gnu 
--incdir=/usr/include/x86_64-linux-gnu 
--cc=cc 
--cxx=g++ 
--enable-gpl 
--enable-shared 
--disable-stripping 
--disable-decoder=libopenjpeg 
--disable-decoder=libschroedinger 
--enable-avresample 
--enable-avisynth 
--enable-gnutls 
--enable-ladspa 
--enable-libass 
--enable-libbluray 
--enable-libbs2b 
--enable-libcaca 
--enable-libcdio 
--enable-libflite 
--enable-libfontconfig 
--enable-libfreetype 
--enable-libfribidi 
--enable-libgme 
--enable-libgsm 
--enable-libmodplug 
--enable-libmp3lame 
--enable-libopenjpeg 
--enable-libopus 
--enable-libpulse 
--enable-librtmp 
--enable-libschroedinger 
--enable-libshine 
--enable-libsnappy 
--enable-libsoxr 
--enable-libspeex 
--enable-libssh 
--enable-libtheora 
--enable-libtwolame 
--enable-libvorbis 
--enable-libvpx 
--enable-libwavpack 
--enable-libwebp 
--enable-libx265 
--enable-libxvid 
--enable-libzvbi 
--enable-openal 
--enable-opengl 
--enable-x11grab 
--enable-libdc1394 
--enable-libiec61883 
--enable-libzmq 
--enable-frei0r 
--enable-libx264
--enable-libopencv
  libavutil      54. 31.100 / 54. 31.100
  libavcodec     56. 60.100 / 56. 60.100
  libavformat    56. 40.101 / 56. 40.101
  libavdevice    56.  4.100 / 56.  4.100
  libavfilter     5. 40.101 /  5. 40.101
  libavresample   2.  1.  0 /  2.  1.  0
  libswscale      3.  1.101 /  3.  1.101
  libswresample   1.  2.101 /  1.  2.101
  libpostproc    53.  3.100 / 53.  3.100
```

