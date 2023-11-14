$ apt update -y && apt upgrade -y
pkg install python3
pkg install git
git clone https://github.com/ratualfa/TikFamous
cd TikFamous
pip3 install -r requirements.txt
python3 Run.py
