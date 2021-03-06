## Webcam_face_recognition

[![LICENSE](https://img.shields.io/badge/license-Anti%20996-blue.svg)](https://github.com/996icu/996.ICU/blob/master/LICENSE)  [![996.icu](https://img.shields.io/badge/link-996.icu-red.svg)](https://996.icu)

This is a super simple demo of running [face recognition](https://github.com/ageitgey/face_recognition) through your computer webcam.
* Just use the browser as a simple client. It's much lighter than a client built with opencv, you can even run it on an ARM device like the Raspberry Pi.
* Web server built by the [sanic](https://github.com/huge-success/sanic). 
* The database uses the simplest sqlite.


## Related Projects

* [face_recognition](https://github.com/ageitgey/face_recognition)

* [sanic](https://github.com/huge-success/sanic)

* [opencv](https://github.com/opencv/opencv)


## Requirements

* Python3.6+

## Installation

To install this project, simply use [pipenv](http://pipenv.org/) (or pip, of course):

```
$ git clone https://github.com/hohocho/webcam_face_recognition.git
$ cd webcam_face_recognition
$ pipenv install
```

Satisfaction guaranteed.

## Usage

```shell
python run.py
```
If you want to deploy the service remotely, you must use **https** ([Why?](https://goo.gl/rStTGz))
