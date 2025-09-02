---
title: Signed request example
excerpt: >
  Demonstrates a signed GET call requiring `SignatureAuth` (and optionally mTLS
  if globally enabled).


  **Required headers**: `Authorization`, `x-date`, `x-nonce`, `x-content-sha256`
  (for GET, hash of empty string).
api:
  file: openapi.yaml
  operationId: get_v1-examples
hidden: false
---