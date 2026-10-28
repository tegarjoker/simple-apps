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

sonar-scanner-npm \
  -Dsonar.host.url=http://172.23.13.82:9000 \
  -Dsonar.token=sqp_c44e0018a7196d63e4be65b1bf37b7de13dfe7c6 \
  -Dsonar.projectKey=simple-apps

sonar-scanner \
  -Dsonar.projectKey=simple-apps \
  -Dsonar.sources=. \
  -Dsonar.host.url=http://172.23.13.82:9000 \
  -Dsonar.token=sqp_c44e0018a7196d63e4be65b1bf37b7de13dfe7c6
