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