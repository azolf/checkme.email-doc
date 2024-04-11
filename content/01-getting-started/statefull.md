---
title: "Statefull"
draft: false
weight: 20
---

If you want to cache the email addresses in a database you should use this.

You could easily run it with docker-compose.

1. Download the docker-compose file
```
    wget https://raw.githubusercontent.com/azolf/checkme.email/main/examples/docker-compose.yml
```

2. Run the setup
```
docker compose run --rm checkme /app/bin/setup
```

3. Fire up the containers
```
docker compose up -d
```
