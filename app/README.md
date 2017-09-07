# A/B Testing

## Overview

A/B testing is a user research technique, which is used to test
which among the A or B version is better design.

For a commercial marketplace the success metric could be
calculated based on "conversion rate".

## What does this project do?

This project does simple A/B testing, of 2 versions of a website.

The metrics collected could then be used to see which version 
among the baseline or variant 
performed better.

# Running the flask server

## Running locally

### Method 1:
 export FLASK_APP=app.py
 flask run

### Method 2:
 python app.py


## Running on github?

 TODO?

## Sample Output:

Creates output file of the following format.

Aarthis-iMac:a-b-testing aarthi$ cat ab_testing.csv
Version,pageLoadTime,clickTime
B,2017-09-06 19:50:05.202000,2017-09-06 19:50:06.484000
A,2017-09-06 19:50:08.579000,2017-09-06 19:50:09.284000
