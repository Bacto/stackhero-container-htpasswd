# stackhero-container-htpasswd

```
docker build -t htpasswd .
```

```
docker run \
  --entrypoint htpasswd \
  htpasswd \
  -Bbn testuser testpassword
```
# stackhero-container-htpasswd
