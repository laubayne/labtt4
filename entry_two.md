#Troubleshooting when Connection via Cloud Identity-Aware Proxy Fails
##Notes from someone who is in no way an expert.

After installing Wordpress on my VM, it completely crashed.
Any time I tried to connect to my server, it would spend 5 minutes saying "establishing connection to SSH server..." before eventually saying "Connection via Cloud-Identity Aware Proxy Failed."

###Steps to Troubleshoot
1. Retry without Cloud Identity-Aware Proxy, as you may be able to bypass it.
2. Click on "troubleshoot."
	1. Follow steps of the troubleshoot. It likely will say that the Cloud-Identity Aware Proxy API has not been used or is disabled.
	2. Follow steps to enable API, if necessary.
	3. Give it a few minutes and try again. 
3. If all else fails, reboot your server. There could be an issue with the RAM, especially on smaller servers.
4. If you are willing to spend a little more money, you can upgrade your VM storage and machine type so this does not happen again. 


No matter what, *do not panic.* Rebooting the server should not delete your data. 

This is not the prettiest description of troubleshooting, but I hope it helps!
