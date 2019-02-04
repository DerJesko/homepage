---
title: "Multiple IPs one network interface"
date: 2019-02-04T19:56:29+01:00
---
Today I've solved a problem which I have been struggling with for a few our.
So I just wanted write this down so I maybe don't forget.
I wanted to configure a network interface on a server to have 2 static IPs.
I followed [this guide](https://askubuntu.com/questions/313877/how-do-i-add-an-additional-ip-address-to-etc-network-interfaces) but my version of debian doesn't have `ifup` so I use `ip a set eth1 up` which didn't work.
After a full restart the changes applied.
However maybe `ip l set eth1 up` would have worked or just `/etc/init.d/networking restart`.
