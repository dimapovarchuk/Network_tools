# Network_tools

Host 8.8.8.8 

<img width="317" alt="image" src="https://user-images.githubusercontent.com/52627259/223471950-a47e8e48-f391-4ea7-9a98-2d6c57eb40ba.png">

host google.com

<img width="323" alt="image" src="https://user-images.githubusercontent.com/52627259/223502221-fe139ac5-35c0-4dd9-8071-a8b60fec99b9.png">

Ping 

ping google.com 

ping 8.8.8.8 

ping -c 3 google.com 

<img width="434" alt="image" src="https://user-images.githubusercontent.com/52627259/223502533-9bd16b6d-6be7-49cb-8a66-206706d35f9e.png">

Curl 

curl -v telnet://192.168.33.10:22 

curl ftp://ftptest.net 

curl http://google.com -I 

<img width="459" alt="image" src="https://user-images.githubusercontent.com/52627259/223502801-f636304f-a798-42e6-865a-b4c1f1110e6b.png">

nc (netcat) 

nc -v -n 192.168.33.10 22 

<img width="277" alt="image" src="https://user-images.githubusercontent.com/52627259/223503054-77d97176-9a66-40fa-90ba-b5f6777bb614.png">

Nmap 

sudo nmap -sn <Your-IP> 

sudo nmap -O <Your-IP> 

<img width="425" alt="image" src="https://user-images.githubusercontent.com/52627259/223503251-d619867a-77c2-4837-800e-5695d4933b06.png">

sudo nmap -sS -sU -PN <Your-IP> 

<img width="465" alt="image" src="https://user-images.githubusercontent.com/52627259/223503448-8fde5f0d-7ac1-4091-bea6-298749c402df.png">

sudo nmap -sT <Your-IP> 

<img width="431" alt="image" src="https://user-images.githubusercontent.com/52627259/223503711-e5df0857-47d0-4da8-b721-c13b059c74ab.png">

sudo nmap -A -T4 <Your-IP> 

<img width="446" alt="image" src="https://user-images.githubusercontent.com/52627259/223504052-7ada9e74-1683-4d49-91f4-081859f4970d.png">

telnet 

telnet 142.251.39.14 

<img width="287" alt="image" src="https://user-images.githubusercontent.com/52627259/223504284-52aa1a49-668d-4631-911f-001c3c4619a0.png">

route 

route 

route -n 

<img width="457" alt="image" src="https://user-images.githubusercontent.com/52627259/223504463-354a4a11-e2a5-4f92-85e8-6ba77d801b63.png">

wget 

wget -e use_proxy=yes http_proxy=<proxy_host:port> http://externalsite.com 

wget www.google.com 

<img width="472" alt="image" src="https://user-images.githubusercontent.com/52627259/223504621-c2a61d9b-ebcc-4051-9718-b64c29514c04.png">

ip (ifconfig) 

ip addr 

<img width="464" alt="image" src="https://user-images.githubusercontent.com/52627259/223504824-01c2164a-4325-4b48-9ecd-1bb9e9d25c20.png">

ip a | grep eth0  | grep "inet" | awk -F" " '{print $2}' 

<img width="416" alt="image" src="https://user-images.githubusercontent.com/52627259/223505167-2ec97a6b-796f-4331-820f-1f96e82839b2.png">

ip a show enp0s3 

<img width="455" alt="image" src="https://user-images.githubusercontent.com/52627259/223505318-7d6449e0-b341-477f-bee5-f4a85708a35c.png">

ip route 

ip route list 

<img width="431" alt="image" src="https://user-images.githubusercontent.com/52627259/223505695-a8d13619-9e85-4656-8c74-1e3f3d8266de.png">

arp 

arp 

<img width="454" alt="image" src="https://user-images.githubusercontent.com/52627259/223505872-b976982e-f180-4d66-a869-b4fa96a73087.png">

ss (netstat) 

ss 

<img width="466" alt="image" src="https://user-images.githubusercontent.com/52627259/223506092-9e6f6882-64b7-4a7b-b54b-0d07a94778bb.png">

ss -ta 

ss -ua 

<img width="460" alt="image" src="https://user-images.githubusercontent.com/52627259/223506579-6696dbbc-f39a-4a19-a407-3d1ca52957dc.png">

ss -xa 

<img width="479" alt="image" src="https://user-images.githubusercontent.com/52627259/223506717-f0253d0f-14ba-4028-861f-571b1dce6bc6.png">

ss -lt 

ss -t -r state established 

ss -t -r state listening 

<img width="461" alt="image" src="https://user-images.githubusercontent.com/52627259/223506964-23031bf3-caa1-4af8-b19d-1354e4e9cd6a.png">

traceroute 

traceroute google.com

<img width="461" alt="image" src="https://user-images.githubusercontent.com/52627259/223507184-9a074038-57e5-445b-aa5f-9565a38718f4.png">

mtr 

mtr google.com 

<img width="469" alt="image" src="https://user-images.githubusercontent.com/52627259/223507302-5e2a4961-87b7-4237-9f06-c3322b2bff45.png">

mtr report 

mtr -n --report google.com 

<img width="415" alt="image" src="https://user-images.githubusercontent.com/52627259/223507472-eb30a68b-6241-4ad9-b5be-1ef1e9c2d49b.png">

dig 

dig twiter.com ANY 

dig google.com ANY +short 

 

dig www.google.com A +short 

dig google.com CNAME +short 

dig google.com MX +short 

<img width="290" alt="image" src="https://user-images.githubusercontent.com/52627259/223507661-f9e8848f-96d7-4388-b328-6bf8f466d682.png">

dig google.com NS +short 

<img width="280" alt="image" src="https://user-images.githubusercontent.com/52627259/223508664-b948f64e-b086-46d9-a3db-a86abfba5b86.png">

dig facebook.com TXT +short 

<img width="403" alt="image" src="https://user-images.githubusercontent.com/52627259/223508850-5a7ba2be-e955-4cab-bc81-2c50e5f0750f.png">

dig -x 8.8.8.8 

<img width="409" alt="image" src="https://user-images.githubusercontent.com/52627259/223509030-da040371-0898-4ceb-b1e4-bf4a5873129a.png">

nslookup 

nslookup google.com 

nslookup 8.8.8.8 

<img width="265" alt="image" src="https://user-images.githubusercontent.com/52627259/223509306-c89a1e2d-b3d6-4508-b38b-6a5e75430a0a.png">

nslookup -type=any google.com 

<img width="289" alt="image" src="https://user-images.githubusercontent.com/52627259/223509407-f5c6037d-3218-433d-a32b-b2b13dbbffa7.png">

Top 

top -u 'username'

<img width="463" alt="image" src="https://user-images.githubusercontent.com/52627259/223509587-4b1f1ced-34f7-4685-836b-ce6b404c70b9.png">

top -i 

<img width="457" alt="image" src="https://user-images.githubusercontent.com/52627259/223509733-23db81e2-df23-46ff-bf9e-44f6b7f56a56.png">

top -d 5 

<img width="433" alt="image" src="https://user-images.githubusercontent.com/52627259/223509866-ebc68c3c-f612-4a57-99fb-290c2480ced7.png">

top -n 2 

<img width="443" alt="image" src="https://user-images.githubusercontent.com/52627259/223509984-084937e7-ab8c-4b57-a524-6852410e0135.png">

Htop 

htop [-dChusv] 

<img width="465" alt="image" src="https://user-images.githubusercontent.com/52627259/223510204-6e2e54bd-feda-4d4f-9017-de05b0a5777f.png">

htop -u username 

<img width="457" alt="image" src="https://user-images.githubusercontent.com/52627259/223510304-dac82905-f590-4fad-9336-8e52269a7231.png">

Ps 

ps -eo pcpu,pid,user,args | sort -k 1 -r | head -10 













