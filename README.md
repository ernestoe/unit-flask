# Flask in nginx/unit

## Build your own

This example based on [nginx docs](unit.nginx.org/howto/docker), feel free to copy and adapt for your own use

```
docker build --tag=ernestoe/flask-unit .
docker push ernestoe/flask-unit
```

Image will be ready to use

```
docker-compose up
```

```
curl -X GET localhost:8080
Hello, World! (Flask)
```
