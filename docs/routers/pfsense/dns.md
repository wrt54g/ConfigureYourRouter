<h2>Change DNS server</h2>
1. Browse to your pfSense (the default ip is <a href="https://192.168.1.1">192.168.1.1</a>)<br>
{% include httpswarning.md %}
2. Enter your login. The default are Username: admin and Password: pfsense (all lowercase).<br>
3. Go to <a href="https://192.168.1.1/system.php">System -> General Setup</a>.<br>
<img src="/ConfigureYourRouter/images/pfsense/dns.png"><br>
4. Select the DNS Server field and enter your new DNS server there.<br>
<img src="/ConfigureYourRouter/images/pfsense/save.png"><br>
5. Click the blue Save button on the bottom.<br>
6. Go to <a href="https://192.168.1.1/services_dhcp.php">Services -> DHCP Server</a>.<br>
<img src="/ConfigureYourRouter/images/pfsense/servers.png"><br>
7. Enter your DNS servers in the DNS Servers fields.<br>
8. Click Save at the bottom.<br>
<img src="/ConfigureYourRouter/images/pfsense/save.png">

You're done!
