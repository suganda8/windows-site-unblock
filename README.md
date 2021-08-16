Windows Site Unblock (Hosts File)
====
The hosts file is a Windows system file that can override DNS and redirect URLs or IP addresses to different locations.

Usage
-----
- Open File Explorer, go to the path : C:\Windows\System32\drivers\etc
- Right-click the hosts file and press properties, In general tab, make sure read-only attribute is unticked.
- Run Notepad as Administrator, Open hosts file from path given above.
- Copy the contents of hosts file in this repository.
- Paste to your hosts file.
- Save.
- Try to open Reddit by accessing it directly without VPN.

Updating IP or Direct URLs
-----
- If something gone wrong with Reddit or any site you listed in hosts file. (Like some part of website doesn't want to load - Infinite loading or just blank)
- Try to Inspect Element by Right-click your browser, then go to Network.
- If there are some red code status such as 404, 403, or else. Check the domain (eg. snoovatar.reddit.com)
- You could do hover the domain (snoovatar.reddit.com) to check the IP of that domain. If this doesn't work in your browser go to IP Checker (ipaddress.com, check-host.net) or just google it "Find website IP Address" and enter the domain website (snoovatar.reddit.com) then IP checker website will tell you the IP.
- And add it to your hosts file manually. (Don't forget to untick the read-only attribute first)
- Example :
- 199.232.69.140    snoovatar.reddit.com

- P.S : IP Address of site could change whenever if the website you unblock gets maintenance or updates.

Status - Updated (2021-08-16)
------
Reddit only