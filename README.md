# homeassistant

1) Install Ubuntu server 18
2) Enable SSH
3) Register DuckDNS.org => run Curl every 5 min to update ISP dynamic IP  https://www.duckdns.org/install.jsp
4) Enable Port forward on home router
5) Install VirtualENV to separate library and runtime   !! Need to study how to utilize container in future
6) Install Home assistant on Ubuntu  https://www.youtube.com/watch?v=OThxdTKVjHU
  - sudo apt install python3-pip
  - sudo apt-get install python3-venv
  - python3 -m venv homeassistant   (Create Virtual environment for Python3)
  # Need to create service with @username.service   without @username  ==> Not gonna work.
  
7) Install Flask with Alexa Jarvis code
8) Build Line bot
9) Install  


# Home assistant with Alexa
https://github.com/walthowd/ha-alexa-tts


10) Configure LetsEncrypt 
# Make sure to complete port forwarding on Router
- git clone https://github.com/letsencrypt/letsencrypt
- ./letsencrypt-auto certonly --email pxxxxxx@yahoo.com -d mxxxxxxxxt.duckdns.org 
![image](https://user-images.githubusercontent.com/16419246/50244308-40949300-0395-11e9-85c2-dc18c787db35.png)


![image](https://user-images.githubusercontent.com/16419246/50244772-64a4a400-0396-11e9-8da3-2c9db2ded7c0.png)


- sudo chmod -R 777 /etc/letsencrypt
![image](https://user-images.githubusercontent.com/16419246/50248445-b4886880-03a0-11e9-8fcf-0ed7d68eb68c.png)
