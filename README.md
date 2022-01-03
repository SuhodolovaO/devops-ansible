# Описание playbook

Playbook содержит 3 плея: установка Java, установка Elasticsearch и установка Kibana.  
Таски, относящиеся к каждому плею, помечены тегами java, elastic и kibana соответственно.  

Параметры для группы all:  
- java_jdk_version: версия Java
- java_oracle_jdk_package: имя копируемого файла с архивом Java

Параметры для группы elasticsearch:
- elastic_version: версия Elasticsearch
- elastic_home: папка для установки Elasticsearch на целевом хосте

Параметры для группы kibana:  
- elastic_host: url хоста Elasticsearch
- kibana_version: версия Kibana
- kibana_home: папка для установки Kibana на целевом хосте