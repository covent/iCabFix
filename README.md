iCabFix
=======

a fix to allow icab mobile browser to upload other files than just pics and videos using iPhone/Ipad devices

IOS devices normally do not allow upload of files different than pictures and videos to web pages (and consequently rouncube with mobile or desktop themes). Icab mobile is a useful browser which has an own download/upload folder (files can be passed to/from it via open in feature) and after a form rewriting allows the upload of any type of file to web pages. To fully support this feature, rc installation needs a little fix in javascript/jquery code used to process the upload, in order to make it compatible with icab form rewriting.
The fix is really simple, ot only requires to add few lines to app.js javascript file present in program/js folder. See app.js file inside this project.

This fix was tested with version 1.0, but should be easily adaptable for next releases.
