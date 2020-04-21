# linux-doc
Documents about learning linux

## CentOS
* List all services
  ```shell script
  systemctl list-unit-files
  ```
  Only show enabled services:
  ```shell script
  systemctl list-unit-files | grep enabled
  ```
