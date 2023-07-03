# network_scan
A terminal script to scan the local network for objects with IP addresses, plus portscan local machine and router.

All scripts are without any kind of warranty, use entirely at your own risk!

On linux place into /user/local/bin/ and change permissions as follows: 
sudo chown root /user/local/bin/netscan.sh 
sudo chmod 755 /user/local/bin/netscan.sh
sudo mv /user/local/bin/netscan.sh /user/local/bin/netscan

Dependancies: nmap, curl
sudo apt-get install -y curl nmap

This terminal script runs a quick security audit to examine the current local network for IP addresses and try and identify them, plus portscanning the local machine and local router throughly for open ports.

END
