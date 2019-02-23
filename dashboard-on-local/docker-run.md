
# Docker run 

## run directly

```sh
docker run -d -p 4040:4040 parseplatform/parse-dashboard --dev --allowInsecureHTTP true --appId parse-app-id --masterKey parse-app-master-key@k8s  --serverURL "http://parse-server.myhost.io:31992" --appName Parse Sever
```