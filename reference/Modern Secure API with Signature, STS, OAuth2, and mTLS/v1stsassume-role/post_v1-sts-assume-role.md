---
title: Issue temporary credentials (STS)
excerpt: |
  Exchange a long-term AK/SK (signed request) for temporary credentials.
  When using the returned credentials, include `x-session-token` in requests.
api:
  file: openapi.yaml
  operationId: post_v1-sts-assume-role
hidden: false
---