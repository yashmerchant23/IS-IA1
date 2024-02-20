commands 
1) install nmap <br />
	sudo apt install nmap
2) ping 172.18.117.20
3) ping the entire server<br />
	nmap -sP 172.18.117.20/20 
4) check for open ports on devices in the network<br />
	sudo nmap -sT -p 80,443 172.18.117.0/20
5) finding what OS the server has<br />
	sudo nmap -O 172.18.117.20
6) Aggresive mode: gives all possible information on the server<br />
	sudo nmap -A 172.18.117.20
7) to find vulnerablities__
	sudo nmap --script vuln 172.18.117.20

