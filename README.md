# kali-tools-addons

## latest updates
sudo apt update && sudo apt-get dist-upgrade -y

## ngrok
curl -s https://ngrok-agent.s3.amazonaws.com/ngrok.asc | sudo tee /etc/apt/trusted.gpg.d/ngrok.asc >/dev/null && echo "deb https://ngrok-agent.s3.amazonaws.com buster main" | sudo tee /etc/apt/sources.list.d/ngrok.list && sudo apt update && sudo apt install ngrok

## testssl.sh
git clone https://github.com/drwetter/testssl.sh.git

## google-chrome
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb

sudo dpkg -i google-chrome-stable_current_amd64.deb

## firefox
https://www.mozilla.org/en-US/firefox/download/thanks/

tar xjf firefox-*.tar.bz2

sudo mv firefox /opt

sudo ln -s /opt/firefox/firefox /usr/local/bin/firefox

sudo wget https://raw.githubusercontent.com/mozilla/sumo-kb/main/install-firefox-linux/firefox.desktop -P /usr/share/applications

## foxy-proxy
https://addons.mozilla.org/en-US/firefox/addon/foxyproxy-standard/

## wappalyzer
https://addons.mozilla.org/en-US/firefox/addon/wappalyzer/

## sec-lists
sudo apt install seclists

## robotsdisallowed
git clone https://github.com/danielmiessler/RobotsDisallowed.git

sudo mv RobotsDisallowed/ /usr/share/wordlists/
