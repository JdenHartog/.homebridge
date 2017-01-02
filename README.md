# homebridge
Some stuff to get [homebridge](https://github.com/nfarina/homebridge) working with [pilight](https://www.pilight.org) on [2016-09-23-raspbian-jessie-lite](https://www.raspberrypi.org/downloads/raspbian/)

sudo apt-get install git-core libavahi-compat-libdnssd-dev make

wget https://nodejs.org/dist/v7.3.0/node-v7.3.0-linux-armv6l.tar.gz<br>
tar -xvf node-v7.3.0-linux-armv6l.tar.gz<br>
cd node-v7.3.0-linux-armv6l<br>
sudo cp -R * /usr/local/<br>

sudo npm install -g homebridge<br>
sudo npm install -g https://github.com/Qonstrukt/homebridge-pilight.git<br>

cd ~/.homebridge<br>
sudo rm config.json<br>
sudo rm -r homebridge<br>
sudo git clone https://github.com/JdenHartog/homebridge.git<br>
sudo mv homebridge/config.json config.json
