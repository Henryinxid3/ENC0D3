apt update && apt upgrade -y
pkg install git
pkg install python
pip install requests
rm -rf ENCODE

cd ENCODE
python3 encode.py
