Why Blocking on Layer 3/4 is effective and efficient
Blocking malicious IPs is simple and effective. On one hand it prevents connections to known bad actors from the beginning and on the other hand, should a client become compromised, communication will be blocked reliably before things may escalate further. Of course this only works as good as the content of the used blocklists is.

While blocking on IP level may seem like a "brute force" approach it is in fact very simple, effective and reliable, it intercepts connections already at Layer 3/4 of the OSI model. Since this happens very early and already on a low level of the networking stack, the costs in terms of performance are almost nothing compared to more sophisticated approaches doing comparable on Layer 7.

Blocking IPs with blocklists on Layer 3/4 is:

Effective
Reliable
Simple to set up and maintain
Comes at almost no performance cost
Certainly there are alternative approaches to achieve comparable results. However nothing beats blocking at Layer 3/4 if one wants to prevent connectivity to a specific IP completely. That said it absolutely makes sense to have complementary measures on other Layers such as DNS blocklists and deep packet inspection in place, also to catch things that might slip through the coarse grained IP Level blocking only.

External blocklists with OPNsense
The use and the management of externally provided IP blocklists with OPNsense is very simple and efficient, aliases are the tool of choice for this.



https://www.allthingstech.ch/using-opnsense-and-ip-blocklists-to-block-malicious-traffic
