# Описание playbook

Playbook содержит 3 плея: установка Elasticsearch, установка Kibana и установка filebeat. Каждый сервис устанавливается на удаленный хост по ssh.  
Каждый плей использует соответствующую роль для установки сервиса.  

Параметры для группы all:  
- elk_stack_version: версия для стека elastic, kibana и filebeat  
- elasticsearch_version: версия Elasticsearch, по умолчанию читается из elk_stack_version  
- kibana_version: версия Kibana, по умолчанию читается из elk_stack_version  
- filebeat_version: версия filebeat, по умолчанию читается из elk_stack_version  
