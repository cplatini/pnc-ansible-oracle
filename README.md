# pnc-ansible-oracle
Ansible Oracle SQL Modules POC

Oracle Server:
Install python module cx_Oracle.
(Install python-pip first, if not installed)
>yum -y install python-pip
>pip install cx_Oracle
Import cx_Oracle:
>python
>$import cx_Oracle
>$exit()

Install Oracle Instant Client
>wget https://download.oracle.com/otn_software/linux/instantclient/195000/oracle-instantclient19.5-basic-19.5.0.0.0-1.x86_64.rpm
>yum  -y install oracle-instantclient19.5-basic-19.5.0.0.0-1.x86_64.rpm

##################

Ansible Server:
Use the oracle.yml and make changes as far as hosts, service name, oracle_home, etc.

Also, copy oracle_sql.py to /usr/share/ansible/plugins/modules/oracle_sql.py


