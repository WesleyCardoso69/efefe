# efefe
wdkmsk
sudo apt-get update
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install build-essential automake libtool libcurl4-openssl-dev libpcre3-dev
sudo apt-get install libsqlite3-dev libreadline5-dev subversion libncurses5-dev
sudo apt-get install libncursesw5-dev libsparsehash-dev libmysqlclient-dev
sudo apt-get install ia32-libs
sudo apt-get install lib32readline5
sudo apt-get install lib32ncursesw5
sudo apt-get install lib32stdc++6
wget http://linux.mtasa.com/dl/140/multith...
tar xnvf multitheftauto_linux-1.4.0.tar.gz
rm multitheftauto_linux-1.4.0.tar.gz
cd multitheftauto_linux-1.4.0/mods/deathmatch
wget http://linux.mtasa.com/dl/140/basecon...
tar xnvf baseconfig-1.4.0.tar.gz
mv -f baseconfig/* ./
rm baseconfig-1.4.0.tar.gz
mkdir resources
cd resources
wget http://mirror.mtasa.com/mtasa/resourc...
unzip mtasa-resources-latest.zip
rm mtasa-resources-latest.zip
cd ../../..
chmod +x mta-server
cd mods
cd deathmatch
sudo apt-get install nano
nano mtaserver.conf
