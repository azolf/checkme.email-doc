---
title: "Stateless"
draft: false
weight: 10
---

With stateless version it doesn't cache the records in the database and everytime check all the validations. You just need to pass env `STATELESS=true` when running the checkme.email.


```
docker run --env VERIFIER_EMAIL=test@example.com \
--env APP_ENV=production \
--env STATELESS=true \
--env AUTH_USERNAME=USERNAME \
--env AUTH_PASSWORD=PASSWORD \
--publish 2525:2525 \
ghcr.io/azolf/checkme:latest \
/app/bin/checkme server
```