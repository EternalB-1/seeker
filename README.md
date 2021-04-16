<h3>This repository was copied: https://github.com/thewhiteh4t/seeker</h3>

<h2>Install:</h2>

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

<h2>Reboot console</h2>

<h2>Use:</h2>

cd seeker

python3 seeker.py -t manual

<h2>In new session:</h2>

ngrok http 8080

<h2>If there was a reconnection error, turn on the wifi hotspot</h2>
