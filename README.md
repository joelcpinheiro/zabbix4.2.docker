## Zabbix Server 4.2 on Docker containers and a Grafana gift
### Access the directory where the files are and build the stack with docker-compose, how describe below:
### Pre-requisites: docker-compose installed 

```sh
docker-compose -f docker-compose_v3-4.2.yaml up -d  
```

### Understanding the hidden files:

The file .env_agent has a configuration of zabbix agent; <br>
The file .env_db_mysql has a configuration of mysql server; <br>
The file .env_srv has a configuration of zabbix server; <br>
The file .env_web has a configuration of webserver nginx; <br>
