# pks-dns-cse
Automate the DNS record creation process for your VMware PKS clusters right from the cluster.
**This is based on the great pks-dns by Chip Zoller. This is adapted to be used with VMware Container Service Extension for vCloud Director. The main difference with the original project is that Enterprise PKS clusters launched with CSE get an unique ID appended to the desired name, therefore, the wrong name is created in the DNS server. With this project, the name is taken from the desired URL (removing the domain name), so the proper DNS record is created.**


Installation instructions and further information can be found in the  original [repo] by Chip Zoller (https://github.com/chipzoller/pks-dns/)
