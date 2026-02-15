apt update -y && apt upgrade -y
pkg install git
pkg install python-pip
git clone https://github.com/briancruz-crypto/Instagram
cd Instagram
pip-install -r requirements.txt
python igfollow.py
