# AutoMySQLBackup

## Defnydd

    wget https://github.com/meigwilym/AutoMySQLBackup/archive/master.zip
    unzip master.zip
    cd AutoMySQLBackup-master
    ./install.sh
    vim /etc/automysqlbackup/myserver.conf

cron

    0 2 * * *  automysqlbackup "/etc/automysqlbackup/myserver.conf"
