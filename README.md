# mediQ @ OxfordHack 2017

![](https://raw.githubusercontent.com/rasmustm/mediq-oxfordhack2017/master/screenshot.png)

## Brief Explanation

This was our submission to the Oxford hackathon OxHack 2017, for the category AI in Healthcare.

We built a web application to give doctors and physicians the ability to record conversations with patients and, based on the voice data collected, receive a brief report of relevant articles related to the diagnosis. The goal was to keep doctors updated with research and assist them in finding diagnoses in a time-efficient manner.

## Getting up and running

The main web application, run with Python Flask, runs on Python 3. The dependencies can be found in requirements.python.txt

To get the system running:

```
$ pip install -r requirements.python.txt
$ cd python-flask && export FLASK_APP=app.py
$ flask run
```
