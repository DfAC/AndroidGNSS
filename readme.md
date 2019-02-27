Android GNSS
===

# Intro

This repo aims to demonstrate how to process Google's GNSS RAW measurements in python, with the main aim of:

* explain the mechanism of calculating GNSS observations, especially pseudorages in Android N;
* it is not per-say intended as a python equivalent of [GPS Measurement Tools from the Goggle](https://github.com/google/gps-measurement-tools) written in Matlab but more a teaching tool, allowing to understand the concepts behind.

## Files

This repo consist of the following:

* **ProcessRanges.ipynb** - explains how to calculate pseudoranges from RAW GNSS measurments, available since Android N. This is python 3.x code based on Paolo et al,2018[^Paolo2018] paper;

## Background informations

* Differences between new API v.24 (Android Nougat 7.0) and previous versions are discussed in:
  * my [2nd Galileo Hackathon presentation](https://www.slideshare.net/LukaszKosmaBonenberg/2nd-galileo-android-hackathon-intro)
  * [Research Seminar Presentation](https://www.slideshare.net/LukaszKosmaBonenberg/pseudoranges-from-your-android-smartphone) at [the Nottingham Geospatial Institute](http://www.nottingham.ac.uk/ngi/).
  * [my slides](https://drive.google.com/file/d/0BytPQTDn3eCFZUNjOUF3RFpLTVk/view) from the Galileo Hackathon held at the [Where Camp Berlin](http://wherecamp.de/).
* [How is Android position calculated](https://developer.android.com/guide/topics/location/strategies.html)
* some other blogs
  * [blackdot GNSS take on ION16's Android GNSS workshop](https://www.blackdotgnss.com/2016/09/20/ppp-with-smartphones-are-we-there-yet/)
  * [bitwise operations in python](https://wiki.python.org/moin/BitwiseOperators)

## Additional links

* [my version of GPS Measurement tools](https://github.com/DfAC/gps-measurement-tools), mostly added notes and easier installation



[^Paolo2018]: Paolo Crosta, Paolo Zoccarato, Rafael Lucas, G. De Pasquale (2018) Dual Frequency Mass-market Chips: Test Results and Ways to Optimize PVT Performance, Proceedings of ION GNSS+ 2018