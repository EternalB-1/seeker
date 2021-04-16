#This repository was copied: https://github.com/thewhiteh4t/seeker

<h3>Install:</h3>

pkg install git

pkg install unrar

git clone https://github.com/EternalB-1/seeker.git

chmod 777 termux_install.sh

./termux_install.sh

unrar e ngrok.rar

mv ngrok ~

cd

chmod +x ngrok

./ngrok authtoken your_token

#Reboot console

#Use:

cd seeker

python3 seeker.py -t manual

#In new session:

ngrok http 8080

#If there was a reconnection error, turn on the wifi hotspot
