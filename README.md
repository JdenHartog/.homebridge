# homebridge
Some stuff to get homebridge working with [pilight](https://www.pilight.org) on [2016-09-23-raspbian-jessie-lite](https://www.raspberrypi.org/downloads/raspbian/)

sudo apt-get install git-core libavahi-compat-libdnssd-dev make  **!!!!!!!!**

wget https://nodejs.org/dist/v7.3.0/node-v7.3.0-linux-armv6l.tar.gz 
tar -xvf node-v7.3.0-linux-armv6l.tar.gz
cd node-v7.3.0-linux-armv6l
sudo cp -R * /usr/local/

sudo npm install -g homebridge
sudo npm install -g https://github.com/Qonstrukt/homebridge-pilight.git
sudo npm install -g homebridge-http ???????

cd /.homebridge/
