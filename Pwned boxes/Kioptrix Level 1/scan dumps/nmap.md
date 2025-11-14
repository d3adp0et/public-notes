-> nmap -p- 10.0.2.3/24

Nmap scan report for 10.0.2.3
Host is up (0.00051s latency).
Not shown: 65516 closed tcp ports (reset)
PORT      STATE    SERVICE
22/tcp    open     ssh
25/tcp    filtered smtp
80/tcp    filtered http
111/tcp   open     rpcbind
139/tcp   open     netbios-ssn
443/tcp   filtered https
993/tcp   filtered imaps
995/tcp   filtered pop3s
1720/tcp  filtered h323q931
3306/tcp  filtered mysql
5900/tcp  filtered vnc
8080/tcp  filtered http-proxy
8888/tcp  filtered sun-answerbook
28716/tcp filtered unknown
30359/tcp filtered unknown
31920/tcp filtered unknown
32768/tcp open     filenet-tms
43692/tcp filtered unknown
52243/tcp filtered unknown
MAC Address: 52:55:0A:00:02:03 (Unknown)

Nmap done: 1 IP address (1 host up) scanned in 878.36 seconds