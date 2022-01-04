# Описание playbook

Playbook содержит 3 плея: установка Elasticsearch, установка Kibana и установка filebeat. Каждый сервис устанавливается на удаленный хост по ssh.    
Таски, относящиеся к каждому плею, помечены тегами elastic, kibana и filebeat соответственно.  

Параметры для группы all:  
- elk_stack_version: версия для стека elastic, kibana и filebeat
