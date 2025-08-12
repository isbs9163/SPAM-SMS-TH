termux          
pkg update -y && pkg upgrade -y && pkg install -y git python python2 python3 nodejs php ruby curl wget nano vim zip unzip tar clang make
pip install --force-reinstall urllib3 six requests
git clone https://github.com/isbs9163/SPAM-SMS-TH
cd SPAM-SMS-TH
python3 PYTH0N-T3ST.py
