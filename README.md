# google-vision-api

Code for Google Vision API.

## Description

Example codes has following features:

* Face Detection
* Landmark Detection
* Logo Detection
* Label Detection
* Text Detection

## Requirement

* Python 3.x
* Credentials from google vision api

## Setup

To install necessary library, simply use pip:

```bash
pip install google-cloud-vision
```

or,

```bash
pip install -r requirements.txt
```

Next, set up to authenticate with the Cloud Vision API using your project's service account credentials. See the [Vision API Client Libraries](https://cloud.google.com/vision/docs/libraries) for more information. Then, set the GOOGLE_APPLICATION_CREDENTIALS environment variable to point to your downloaded service account credentials:

```bash
export GOOGLE_APPLICATION_CREDENTIALS=/path/to/your/credentials-key.json
```

## Quick Start: Running the Example


### Face Detection

Face Detection demo using FACE_DETECTION feature.


```bash
$ python examples/face_detection.py images/face.jpg
```

### Label Detection

Label Detection demo using LABEL_DETECTION feature.


```bash
$ python examples/label_detection.py images/label.jpg
```

### Landmark Detection

Landmark Detection demo using LANDMARK_DETECTION feature.


```bash
$ python examples/landmark_detection.py images/landmark.jpg
```

### Logo Detection

Logo Detection demo using LOGO_DETECTION feature.

```bash
$ python examples/logo_detection.py images/logo.jpg
```

### Text Detection

Text Detection demo using TEXT_DETECTION feature.


```bash
$ python examples/text_detection.py images/text.png
...
```


## Author

[Chhayansh Purohit](https://github.com/chhayanshp11) With ESEM Infostreamz Pvt.Ltd.
