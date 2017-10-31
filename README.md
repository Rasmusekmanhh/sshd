# sshd 8888 portti
1. sudo apt-get install -y puppet
2. sudo apt-get install -y git
3. cd /etc/puppet/modules
4. sudo git clone https://github.com/Rasmusekmanhh/sshd/
5. sudo puppet apply -e 'class{"sshd":}'

sudo git add . && sudo git commit; sudo git pull && sudo git push #jos teet muutoksia, päivitä ne tällä githubiin
