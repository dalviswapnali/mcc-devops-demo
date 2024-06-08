Run Without docker
1) Create a VM
2) SSH into VM (ssh username@ip-address)
3) Update and upgrade system (sudo apt-get update && apt-get upgrade -y)
4) install pip (sudo su
				apt install python3-pip)
				
5) clone your repo (git clone {repo https link}, branch main)
6) install libraries (pip install -r requirements.txt)
7) Run your app (fastapi run app.py)
8) open port 8000 on VM(goto azure vm network setting
						create inbound port rule)
						
