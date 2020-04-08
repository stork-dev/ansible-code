
### Setup

three instance 1 for ansible master, 1 for nginx node and 1 for apache node

edit hosts file and update nginx node ip and apache node ip.

update roles/smtp_message/tasks/send_mail.yaml for sending emails

### Install apache and nginx
``` ansible-playbook site.yaml ```

### Install Java on prod_apache group

``` ansible-playbook install_java.yaml ```


