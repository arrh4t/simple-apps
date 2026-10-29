# Create env variable

```
vim .env
```

```
DB_NAME=training
DB_HOST=ipaddress
DB_USER=peserta
DB_PASS=password
APP_PORT=3000
```
sonar-scanner \
  -Dsonar.host.url=http://172.23.13.195:9000 \
  -Dsonar.token=sqp_332a363a8d3b3c30ebfe3dbe526140e790c67205 \
  -Dsonar.projectKey=Simple-Apps

cat /var/lib//jenkins/secrets/initialAdminPassword
ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIPDbQMTRAjSkN/zCDgYQZt5RJeMXhsGcBDuaLc/U04++ root@devops2-putu