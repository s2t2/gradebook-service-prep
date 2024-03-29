# Professor Rossetti's Gradebook Service (Python)

## [System Objectives](/planning/system-objectives.pdf)

A system which reads gradebook data from Google Sheets, then distributes detailed grade reports to each student via email.

![](/planning/data-flow-diagram.jpg)

## Prerequisites

  + Git
  + Anaconda, Python 3.7, Pip

## Setup

Create a new project in the Google Developer Console. Enable access to the Google Sheets API. Obtain a credentials file, and store it in this repository as "auth/credentials.json".

Setup a virtual environment:

```sh
conda create -n gradebook-env python=3.7
conda activate gradebook-env
```

Install package dependencies:

```sh
pip install -r requirements.txt
```

## Usage

```sh
python notification_service.py
```

## [License](/LICENSE.md)
