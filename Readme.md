# For Sysmtemd V2 Add this Config

vim /etc/docker/daemon.json
```
{"userns-remap": "default"}
```
## Restart Docker Service and Bring up FREEIPA
```
service docker restart

docker compose up -d
```

# Here is Our Scenario
![authelia](https://github.com/farshadnick/authelia-Freeipa-dockercompose/assets/88557305/b9a5cd97-f5a7-4032-843c-47859a07be6b)
