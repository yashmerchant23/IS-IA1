commands 
1) install nmap__
	sudo apt install nmap
2) ping 172.18.117.20__
3) ping the entire server__
	nmap -sP 172.18.117.20/20 
4) check for open ports on devices in the network__
	sudo nmap -sT -p 80,443 172.18.117.0/20
5) finding what OS the server has__
	sudo nmap -O 172.18.117.20
6) Aggresive mode: gives all possible information on the server__
	sudo nmap -A 172.18.117.20
7) to find vulnerablities__
	sudo nmap --script vuln 172.18.117.20

