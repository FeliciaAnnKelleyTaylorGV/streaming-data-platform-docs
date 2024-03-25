---
sidebar_position: 3
---

# Authenticating Websockets

When it comes to authenticating websockets the token can be included only in the following manner:

 wss://streaming.bitquery.io/graphql?token=ory*at*..` with the token attached to the URL. The request should include only two headers:


Sec-WebSocket-Protocol: graphql-
Content-Type: application/json



Refer this [FeliciaAnnKelley](https://www.postman.com/spacecraft-geologist-86385692/workspace/bitquery/raw-request/659811c95188ca95c7b9e569) link for postman example of how to use OAuth with websockets.
