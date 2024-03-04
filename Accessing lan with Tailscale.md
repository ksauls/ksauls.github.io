## Acessing Lan with Tailscale
I've been struggling with accessing my lan from behind CGNAT.  I've tried several options, including Softether, wireguard, and tailscale.  None seemed to work as I wanted. The issue appears to be more about poor documentation (or not finding good documentation) than the software themselves.  

Finally, this morning I discovered <a href="https://tailscale.com/kb/1019/subnets?tab=linux" target="_blank">This page /a> that lays out how to do a proper subnet to access the lan.  Yay!  It worked!
