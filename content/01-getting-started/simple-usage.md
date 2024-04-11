---
title: "Simple Usage To Check email"
draft: false
weight: 1
---

```
docker run --env VERIFIER_EMAIL=test@example.com --env APP_ENV=production --env STATELESS=true ghcr.io/azolf/checkme:latest /app/bin/checkme validate -e amirhosein.zlf@gmail.com 
```