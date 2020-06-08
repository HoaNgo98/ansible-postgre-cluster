# ansible-postgre-cluster
MÔ HÌNH POSTGRE CLUSTER 3 NODE: 1 master, 2 slave
# deploy
+ ansible-playbook -i postgre.hosts postgre.yml --tags setup
+ ansible-playbook -i postgre.hosts postgre.yml --tags config
