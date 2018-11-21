#Guida per utilizzare script autovoto
 
 
sudo apt-get install git -y && sudo apt-get install python-httplib2 python-requests python-yaml -y
git clone https://github.com/simonmorgenthaler/Lisk-autoVote
cd Lisk-autoVote
nano config.yml
 
#Modificare node,mySecret,mySecondSecret,myAddress,myPublicKey
 
#Salvare con ctrl + x e dare comando "y"
 
 
#Eseguire dentro la cartella Lisk-autoVote
nano votes.txt
./autoVote.py
