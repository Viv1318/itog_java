## Task 1
mkdir Animals    
cd ~/Animals    
cat > home_animals    
cat > pack_animals    
cat home_animals pack_animals > oll_animals    
cat oll_animals    
mv oll_animals mans_friends    
ls -ali 

## Task 2   
mkdir Animals_system    
cd ~/Animals    
mv mans_friends ~/Animals_system    
cd ~/Animals_system    
ls -ali

## Task 3
sudo wget https://dev.mysql.com/get/mysql-apt-config_0.8.23-1_all.deb    
sudo dpkg -i mysql-apt-config_0.8.23-1_all.deb    
sudo apt-get update    
sudo apt-get install mysql-server

## Task 4
sudo wget https://download.docker.com/linux/ubuntu/dists/jammy/pool/stable/amd64/docker-ce-cli_20.10.13~3-0~ubuntu-jammy_amd64.deb    
sudo dpkg -i docker-ce-cli_20.10.13~3-0~ubuntu-jammy_amd64.deb  
sudo dpkg -r docker-ce  
sudo dpkg -r docker-ce-cli 