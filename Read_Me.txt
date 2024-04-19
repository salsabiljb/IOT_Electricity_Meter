1/version influxdb installée :influxdb-1.8.10-1
wget https://dl.influxdata.com/influxdb/releases/influxdb-1.8.10_windows_amd64.zip -UseBasicParsing -OutFile influxdb-1.8.10_windows_amd64.zip
Expand-Archive .\influxdb-1.8.10_windows_amd64.zip -DestinationPath 'C:\Program Files\InfluxData\influxdb\'
2/CREATE DATABASE MP_IOT
 USE MP_IOT
3/version grafana installée : 6.7.2
4/Dans node-red le noeud: MP_IOT_Backup , il faut changer le path de fichier pour  faire le stockage des valeurs. 
Exemple : C:\Users\marie\OneDrive\Bureau\MP_IOT_Backup_Courant1.csv 
