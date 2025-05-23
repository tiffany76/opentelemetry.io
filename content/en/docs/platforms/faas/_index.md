---
title: Functions as a Service
linkTitle: FaaS
description: >-
  OpenTelemetry supports various methods of monitoring Function-as-a-Service
  provided by different cloud vendors
redirects: [{ from: /docs/faas/*, to: ':splat' }] # cSpell:disable-line
---

Functions as a Service (FaaS) is an important serverless compute platform for
[cloud native apps]. However, platform quirks usually mean these applications
have slightly different monitoring guidance and requirements than applications
running on Kubernetes or Virtual Machines.

The initial vendor scope of the FaaS documentation is around Microsoft Azure,
Google Cloud Platform (GCP), and Amazon Web Services (AWS). AWS functions are
also known as Lambda.

### Community Assets

The OpenTelemetry community currently provides pre-built Lambda layers able to
auto-instrument your application as well as the option of a standalone Collector
Lambda layer that can be used when instrumenting applications manually or
automatically.

The release status can be tracked in the
[OpenTelemetry-Lambda repository](https://github.com/open-telemetry/opentelemetry-lambda).

[cloud native apps]: https://glossary.cncf.io/cloud-native-apps/
