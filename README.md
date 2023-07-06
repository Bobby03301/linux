
###### /opt/oracle/instantclient_21_4/network/admin
###### https://www.geeksforgeeks.org/how-to-install-sqlplus-on-linux/

## SERVICE_NAME
ORCL =
   (DESCRIPTION =
     (ADDRESS_LIST =
       (ADDRESS = (PROTOCOL = TCP)(HOST = database-1.ci3kdif6dctu.us-east-1.rds.amazonaws.com)(PORT = 1521))
     )
     (CONNECT_DATA =
       (SERVICE_NAME = ORCL)
     )
   )

## SID
   ORCL =
   (DESCRIPTION =
     (ADDRESS_LIST =
       (ADDRESS = (PROTOCOL = TCP)(HOST = database-1.ci3kdif6dctu.us-east-1.rds.amazonaws.com)(PORT = 1521))
     )
     (CONNECT_DATA =
       (SID = ORCL)
     )
   )
