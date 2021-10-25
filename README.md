#install
pkg update && pkg upgrade

pkg install python2

pkg install git

git clone https://github.com/vikoganz/ndolon

cd ndolon

pip2 install -r zona.ndolon

python2 ndolon.py
