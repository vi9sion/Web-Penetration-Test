# Web-Penetration-Test 
API Testing tools 

Download Kali

Open Terminal
sudo apt update -y 
sudo apt upgrade -y
sudo apt dist-upgrade -y

Open BurpSuite
add extension - Autorize 
download Jypton
add download to python environment 
install Autorize 

Install FoxyProxy in Firefox
add BurpSuite 127.0.0.1 port 8080
add Postman   127.0.0.1 port 5555
Download CA certificate 

Open Terminal
install Postman
sudo wget https://dl pstmn.io/download/latest/linux64 -O postman-linux-x64.tar.gz
sudo tar -xvzf postman-linux-x64.tar.gz -C /opt 
sudo ln -s /opt/Postman/Postman /usr/bin/postman 

Put tools in /opt
sudo pip3 install mitmproxy2swagger 
sudo apt-get install git 
sudo apt-get install docker-compose 
sudo apt-get install docker.io 
sudo apt install golang-go

Install jwt_tool
sudo git clone https://github.com/ticarpi/jwt_tool 
cd jwt_tool
pyton3 -m pip install termcolor cprint pycryptodomex requests 
sudo chmod +x jwt_tool.py
sudo ln -s /opt/jwt_tool/jwt /usr/bin/jwt_tool

Install kiterunner
sudo git clone https://github.com/assetnote/kiterunner.git 
cd kiterunner 
sudo make build 
cd dist 
ls
sudo ln -s /opt/kiterunner/dist/kr /usr/bin/kr 
cd /opt 

Install Arjun
sudo git clone https://github.com/s0md3v/Arjun.git
cd Arjun
ls
sudo python3 setup.py install

Install Zap 
sudo apt install zaproxy 
OpenAPI Support 
