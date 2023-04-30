# Ansible playbook для установки Ceph в режиме single-host
=========

Манифест install_single-host.yml устанавливает cephadm и иницилизирует кластер Ceph в режиме single-host, добавляет в OSD все свободные диски и создает пул для использования. 

Требуется
------------

* Ansible 2.10 и новее 
* ОС семейства Linux 

Переменные
------------

FIRST_HOST_MONITOR - IP адрес сервера, на котором устанавливается Ceph
CEPH_USER - имя технической учетной записи
POOL_NAME - Имя пула 
