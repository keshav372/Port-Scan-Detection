# Port-Scan-Detection
Installing Libcap sudo apt-get install libcap-devel 
Installing pcapy: sudo apt-get install pcapy 
Installing dpkt: sudo pip install dpkt   noscan.pcap 
:-when the pacp is scanned there should not show any scans  
GRADING RUBRIC: Null Scan Xmas Scan Udp  Scan ICMP Echo Scan Half Open Scan  
Running the Program: place the python program in the root directory and place the pcap files also in the same directory.  
Open the Terminal and change the directory to the root where port scan detectoin python program is present 
[root@osboxes "path"] python psd.py &lt;filename.pcap> Example: [root@osboxes Documents] python psd.py noscan.pcap
