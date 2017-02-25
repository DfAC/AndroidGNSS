Android GNSS
===

# Intro

This repo is intended as the python implementation of the Google's [GPS Measurement Tools](https://github.com/google/gps-measurement-tools) written in Matlab. The aim of this repo is to:

* explain the mechanism of calculating GNSS observations in Android N
* create python equivalent of [GPS Measurement Tools from the Goggle](https://github.com/google/gps-measurement-tools)

Differences between new API v.24 (Android Nougat 7.0) and previous versions can be found on:

* [my slides](https://drive.google.com/file/d/0BytPQTDn3eCFZUNjOUF3RFpLTVk/view) from the Galileo Hackathon held at the [Where Camp Berlin](http://wherecamp.de/). 
* [Research Seminar Presentation](https://www.slideshare.net/LukaszKosmaBonenberg/pseudoranges-from-your-android-smartphone) at [the Nottingham Geospatial Instute](http://www.nottingham.ac.uk/ngi/).


## Files

* **ProcessRanges.ipynb** - explains how to calculate pseudoranges from Android N data, roughly equivalent of `ProcessGnssMeas.m`


## Background informations

* [How is Android position calculated](https://developer.android.com/guide/topics/location/strategies.html)
* [blackdot GNSS take on ION16's Android GNSS workshop](https://www.blackdotgnss.com/2016/09/20/ppp-with-smartphones-are-we-there-yet/)
* [bitwise operations in python](https://wiki.python.org/moin/BitwiseOperators)

## Additional links

* [my version of GPS Measurement tools](https://github.com/DfAC/gps-measurement-tools), mostly added notes and easier installation

