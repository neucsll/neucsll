pkg update -y && upgrade -y
pkg install git -y python3 -y
pkg install python3-pip
pkg install openssl
pip install requests bs4 
git clone https://github.com/DataSC3/noblack-mail.git
cd noblack-mail
python3 noblack-mail.py
