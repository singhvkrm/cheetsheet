# cheetsheet
//boot
ipmitool -I lanplus -H 192.168.1.xx -U root -P ADMIN chassis bootdev pxe options=persistent
//acitive
ipmitool -I lanplus -H 192.168.1.xx -U root -P ADMIN sol activate
//power
ipmitool -I lanplus -H 192.168.1.xx -U root -P ADMIN power reset

