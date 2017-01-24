msjnc -- MadScientist JNC Session Manager
=============================================================

This script manages the Juniper Network Connect VPN service.  It is a
replacement for the HTML/Java based toolkit provided by Juniper.


Installation
------------

Download and make executable (by running `chmod 755 msjnc`), then run.

You can find the utility in your applications menu, or invoke it directly from
the command line.

Full documentation is available by running `perldoc msjnc`.

-------------------------
[![Flattr this git repo](http://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=madscientist&url=https://github.com/madscientist/msjnc&title=MadScientist JNC Session Manager&language=&tags=github&category=software)

## For NTU VPN

1. Install Juniper VPN according to this post: <http://ccnet.ntu.edu.tw/vpn/for-ubuntu.html>
1. Checkout this repository
1. ./set-profile.sh
    ![](http://i.imgur.com/O0hYCy3s.jpeg)
1. ./connect.sh `Profile Name`
1. ./disconnect.sh
