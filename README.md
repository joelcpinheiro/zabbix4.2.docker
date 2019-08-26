## Zabbix Server 4.0 on Docker containers
### Access the directory where the files are and build the stack with docker-compose, how describe below:
```sh
docker-compose up -f docker-compose_v3.yaml -d . 
```

### Understanding the hidden files:

The file .env_agent has a configuration of zabbix agent; <br>
The file .env_db_mysql has a configuration of mysql server; <br>
The file .env_srv has a configuration of zabbix server; <br>
The file .env_web has a configuration of webserver nginx; <br>
