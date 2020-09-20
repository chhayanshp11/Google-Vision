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

![Face Detection](images/face.jpg)

```bash
$ python examples/face_detection.py images/face.jpg
Joy Likelihood: 1
Joy Likelihood: 5
```

### Label Detection

Label Detection demo using LABEL_DETECTION feature.

![Label Detection](images/label.jpg)

```bash
$ python examples/label_detection.py images/label.jpg
Labels:
laptop
electronic device
technology
netbook
computer keyboard
personal computer
gadget
```

### Landmark Detection

Landmark Detection demo using LANDMARK_DETECTION feature.

![Landmark Detection](images/landmark.jpg)

```bash
$ python examples/landmark_detection.py images/landmark.jpg
Found landmark: Statue of Liberty
```

### Logo Detection

Logo Detection demo using LOGO_DETECTION feature.

![Logo Detection](images/logo.jpg)

```bash
$ python examples/logo_detection.py images/logo.jpg
Found logo: Starbucks
```

### Text Detection

Text Detection demo using TEXT_DETECTION feature.

![Text Detection](images/text.png)

```bash
$ python examples/text_detection.py images/text.png
The Daily News
The martians have come at last
Lorem Ipsum is simply dummy Lorem Ipsum is simply dummy
text of the printing and typesettingext of the printing and typesetting
industry. Lorem Ipsum has been industry. Lorem Ipsum has been
the industry's standard dummy the industry's standard dummy
text ever since the 1500s, when text ever since the 1500s, whern
an unknown printer took a galley an unknown printer took a galley
of type and scrambled it to make of type and scrambled it to make
a type specimen book. It has a type specimen book. It has
survived not only five centuries survived not only five centuries
, but also the leap into electronic , but also the leap into electronic
...
```


## Author

[Chhayansh Purohit](https://github.com/chhayanshp11) With ESEM Infostreamz Pvt.Ltd.
