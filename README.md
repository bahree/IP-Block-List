# IP Block List
IP addresses and some other rules, that I block on the firewall at untangle.

These are in json format that you can import in the untangle firewall app and edit there. If you want just the list of IP's you should be able to pull this out.

There are the following rules that I have implemented - you of course can change them as you see fit.


1. Block IPs - Part 1 - Long list of IP's that are blocked - any traffic coming from these dont get in.
2. Block IPs - Part 2 - Part 1 got too big, so started a new on to make it more manageable. 
3. Block Camera IPs - I have a number of cameras at home that monitor and record also send some telemetary home and this blocks those.
4. Block Specific Countries - I block traffic for some countries. Some of these rules can dynamically change depending on other rules. Right now the following countries are blocked: RU,VN,KP,UA,BR,TR,RO,PK
5. Block IPs - WyzeCam - There are some IP's that Wyzecam was reaching out too, this blocks that.
6. Block China - This is seperated from the other list, as sometimes I need to manage rules differently to block traffic originating from China.

These work for me, feel free to change and tweak. If you do have other IP addresses, please share that over so I can add them here. 
