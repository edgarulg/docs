---
title: Create Client Credentials
linktitle: Create Client Credentials
description: >
  Create machine-to-machine client credentials in Armory Armory CD-as-a-Service.
---

## Overview

Client credentials are machine-to-machine credentials that the CLI uses to authenticate with your Armory CD-as-a-Service environment when you trigger deployments as part of an external automated workflow. These credentials are passed through the `clientID` and `clientSecret` parameters.

## How to create client credentials

{{< include "cdaas/client-creds.md" >}}

Armory recommends that you store these credentials in a secret engine that is supported by the tool you want to integrate with Armory CD-as-a-Service.