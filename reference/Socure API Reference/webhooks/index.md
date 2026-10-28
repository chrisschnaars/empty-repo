---
title: Webhooks
excerpt: >-
  Webhooks allow you to receive real-time notifications when an event occurs.
  Details about the event are sent via 

  an HTTP `POST` request to the URL you specify.


  When you receive a new event, you must return a `200` HTTP status code. If you
  do not send a `200` response, Socure attempts to redeliver the event. After
  five failed attempts over two days, the event delivery is marked as a failure
  and the webhook is disabled.

  **Note**: For auto-enrolled transactions, Socure attempts to redeliver the
  notification until it is successfully received.
hidden: false
---