# TP2-Global-Projet

Ce TP est rendu par le groupe Arnaud VINSON et Thomas PONS.

Tous les conteneurs demandé ont été mis en place :

- SWAG
- Heimdall
- Matomo
- ZAP
- DHCP
- DNS
- LDAP
- Syslog
- Zabbix
- Wireshark
- Wireguard
- Portainer

Nous avons ajouté Portainer afin d'avoir un visuel sur l'ensemble de notre TP.

Duckdns nous a permis d'obtenir un DNS, ici tomscop.duckdns.org.

SWAG est configuré afin de distribuer les conteneurs asociés en "subdomains" pour des raisons de compatibilité.

Ces services sont disponible depuis un navigateur web :
- Heimdall  = https://tomscop.duckdns.org
- Matomo    = https://matomo.tomscop.duckdns.org
- Zabbix    = https://zabbix.tomscop.duckdns.org
- Zap       = https://zap.tomscop.duckdns.org
- Wireshark = https://wireshark.tomscop.duckdns.org
- Portainer = https://portainer.tomscop.duckdns.org
- LDAP      = https://phpldapadmin.tomscop.duckdns.org

Le serveur DHCP distribue correctement les adresses et le serveur DNS associe bien les noms DNS de chacun.

Le serveur de log stock l'ensemble des logs sur la machine hote dans le dossier indiqué dans le docker-compose.

Le service LDAP est disponible et opérationnel afin de gérer l'ensemble du domain "tomscop.duckdns.org".

Wireguard est configurer en mode serveur afin de permettre a des client de se connecter a celui-ci en créant un tunnel entre les deux appareils.

