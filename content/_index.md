---
title: checkme.email Documentation
description: checkme.email Documentation
images:
- images/pexels-photo-196666.jpeg
---

# checkme.email Documentation

checkme is an open-source project designed to simplify the setup of an SMTP server with built-in email address validation. Leveraging the powerful [trueMail](https://github.com/truemail-rb/truemail) library, checkme ensures that email addresses are validated before being sent, enhancing the reliability and deliverability of your emails. This image show how the SMTP server works.

## Features

* Email Address Validation: checkme integrates seamlessly with the trueMail library, allowing for robust email address validation to ensure the accuracy of recipient addresses.

* Customizable Validations: Tailor the validation process to your specific requirements by customizing the types of validations performed on email addresses.

* Stateful Mode: Enhance performance and reduce redundancy with the option to run checkme in a stateful mode. This mode caches all validations in a PostgreSQL database, preventing multiple checks for regularly used email addresses.
