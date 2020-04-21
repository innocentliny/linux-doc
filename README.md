# linux-doc
Documents about learning linux

## CentOS
* systemctl
  * enable service
    ```shell script
    systemctl enable <service>
    ```
  * start / stop / restart service
    ```shell script
    systemctl start <service>
    systemctl stop <service>
    systemctl restart <service>
    ```
  * list all services
    ```shell script
    systemctl list-unit-files
    ```
    Only show enabled services:
    ```shell script
    systemctl list-unit-files | grep enabled
    ```
* firewall
  * open service
    ```shell script
    firewall-cmd --zone=public --permanent --add-service=postgresql
    firewall-cmd --reload
    ```
