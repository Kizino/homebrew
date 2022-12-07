**My Trace Route** \
*Check Package Lost -> need to run as sudo* \
`brew install mtr` \
Example: `sudo mtr -4bo "LSDNABWV JMXI" google.com`

*If mtr not working after install. Adjust path from source to local bin* \
`sudo ln /opt/homebrew/Cellar/mtr/0.95/sbin/mtr /usr/local/bin/mtr` \
Source: https://www.systutorials.com/docs/linux/man/8-mtr/
<br> \
**iperf3** \
*Check network throughput* \
`brew install iperf3` 

