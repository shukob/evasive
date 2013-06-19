mod_evasive_x
=============


Added some features to evasive_module.


Currently only 2.x version is implemented.


Original mod_evasive is [here](http://www.zdziarski.com/blog/?page_id=442).


Used regex library [TRex](http://sourceforge.net/projects/tiny-rex/).


Additions
---------

DOSXForwardedForAsRemoteIP 0 or 1. Use X-Forwarded-For as remoteIP when 1. Defaults to 0.

DOSTargetedURL Regular expression of target URL, e.g. example.com:80/some.path  Multiple entries requires multiple lines.

DOSUnTargetedURL Regular expression of untargeted URL, e.g. example.com:80/some.path  Multiple entries requires multiple lines.

DOSLogOnly 0 or 1. Do not return 403 if 1. Defaults to 0.
