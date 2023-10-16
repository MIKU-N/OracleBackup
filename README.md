# OracleBackup
OracleBuckup file

一个甲骨文ARM实例DD镜像
- 用户名:root
- 密码:10086.fit
来自 https://10086.fit/1222

```
cd /root && wget -cO debian.sdb.gz https://github.com/MIKU-N/OracleBackup/raw/main/dabian.sdb.gz?download=
gzip -dc /root/debian.sdb.gz | dd of=/dev/sdb
