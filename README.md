pfsense-cpsamplepages
=====================

Captive Portal page samples for PfSense 2.3
---------------------------------------------

Following archives take part of a captive portal to be used with
pfSense 2.3.

There are two samples: GUEST, to build a captive portal without
user authentication but with ToS requirement, and CORP, to build
a captive portal with both ToS and user/password authentication.

Both samples include a ToS text sample (in spanish) to be adapted for our
organisation. In particular, you should replace "TuEmpresa" with your
own company name (these mentions also are written in some php files).

To install these files, you should upload to captive portal (File Manager
tab) all files but captiveportal-login-page.php and
captiveportal-login-error.php. These two files must be uploaded,
respectively, under Portal Page Contents and Authentication
Error Contents options.

Folder "artwork" includes a GIMP file used to generate generic logo
(captiveportal-logo.png), these logo has been created by using several
images available in several websites and Google Images.

Enjoy these files!

Note:
Some files are taken and modified from:
- PfSense Forum ( http://forum.pfsense.org/index.php?topic=59523.0 )
- Centreon monitoring software ( http://www.centreon.com )
- JQuery Mobile site ( http://jquerymobile.com )

