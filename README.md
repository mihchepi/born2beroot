# born2beroot
project ecole 42   
simple setting debian server

## discription
see b2br_discription.yaml

## install server
this install on VirtualBox   
cd init_server   
./init.sh   

Next, manually change sudoers premissions, other should not read   
See output init.sh scripts   

## install WP-PhpMyAdmin-MySQL
cd install_wp
./install_requirements.sh
./start.sh

## install Prometheus-Grafana
I see [this](https://freehost.com.ua/faq/articles/ustanovka-steka-grafanaprometheus-na-debian-10/) manual 
