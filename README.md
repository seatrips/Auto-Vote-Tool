#AutoVote script Guide
 
`` 
sudo apt-get install git -y && sudo apt-get install python-httplib2 python-requests python-yaml -y
``
``
git clone https://github.com/simonmorgenthaler/Lisk-autoVote
``
``
cd Lisk-autoVote
``
``
nano config.yml
``
 
### edit mySecret,mySecondSecret,myAddress,myPublicKey
 
``
nano votes.txt
``
### edit delegates
``
./autoVote.py
``
