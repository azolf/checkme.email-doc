---
title: "Application Mode"
draft: false
weight: 10
---

| Name        | Description                                                                                                                                             | Required              | Default Value |
| ----------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------- | ------------- |
| STATELESS   | When set to true it doesn't need any database configuration and it doesn't cache the email addresses. When set to true the below credentials are needed | No                    | FALSE         |
| DB_NAME     | Database name                                                                                                                                           | Yes if STATELESS=true |               |
| DB_POOL     | Database number of pool connection                                                                                                                      | Yes if STATELESS=true |               |
| DB_USER     | Database username                                                                                                                                       | Yes if STATELESS=true |               |
| DB_PASSWORD | Database password                                                                                                                                       | Yes if STATELESS=true |


