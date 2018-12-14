# centostpl
Plantilla Centos. Aquesta plantilla prepara un sistema CentOS i el deixa apunt. Realitza les tasques:
- yum update
- add epel repo
- hostname
- etc/hosts
- ntp


# Variables
Variables importants a definir per cada host
* hostname: hostname de la màquina. Ex. foner
* hostname_fqdn: hostname complet FQDN. Ex. foner.sint.uib.es
* host_ip4: IPv4 de la interfície eth0
