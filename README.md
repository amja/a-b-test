# A/B Testing

## Why?

This project allowed us to perform an A/B test on two versions of a website we designed to test whether various attributes affected certain important metrics (e.g. dwell time, clickthrough rate). This was for an assignment for CSCI1300: User Interface and User Experience at Brown University.


## Running and testing it locally.
Following command to be run on Mac OS terminal or WINDOWS powershell.

 pip install -r requirements.txt
 python app.py


## Sample Output while testing locally:

Creates output file of the following format.

Aarthis-iMac:a-b-testing aarthi$ cat ab_test.csv
version,pageLoadTime,clickTime,clickHTMLElementId,UniqueSessionID
B,1506176905681,1506176908590,ca1,1506176905390
B,1506176905681,1506176909309,ca2,1506176905390
A,1506176912336,1506176914382,mp2,1506176912222


## Sample output after hosting in heroku.
2017-09-22T04:15:05.318219+00:00 app[web.1]: AB_TESTING: A 1506053696735 1506053705304 mp1 1506053696475
2017-09-22T04:15:07.288130+00:00 app[web.1]: AB_TESTING: A 1506053696735 1506053707279 mp2 1506053696475
2017-09-22T04:15:08.353015+00:00 app[web.1]: AB_TESTING: A 1506053696735 1506053708343 mp2 1506053696475
2017-09-22T04:15:09.444328+00:00 app[web.1]: AB_TESTING: A 1506053696735 1506053709431 mp1 1506053696475
2017-09-22T04:15:14.822574+00:00 app[web.1]: AB_TESTING: B 1506053712624 1506053714784 ca1 1506053712526
2017-09-22T04:15:16.682459+00:00 app[web.1]: AB_TESTING: B 1506053712624 1506053716671 ca2 1506053712526
2017-09-22T04:15:17.769221+00:00 app[web.1]: AB_TESTING: B 1506053712624 1506053717759 ca1 1506053712526

