---
tags: data
---

Webhook purpose is for real-time update on data/information. triggered by events
it delivers data from one app to another immediately 
-> suitable for
- short term event (subscriber, new data added)

Problem
- webhooks are easy to down: midhanlde lose
- customer time-out: weghoosk gets delyed one the request are in queued. hence, the process of trasnfering data gets blocked nad cumbersome prone to multiple layers.
- security layers between sender and receiver usaully is HTTP request protocol. It gets messy once the latency is more than the server can handle. 

How 'events' poll works
- events poll dont get interrupted once the server is down. it keeps a cursor locally where we can trace the latest catch up

On the producer side, to support `/events` you need to add the same ceremony around monitoring creates/updates/deletes as you'd use for webhooks. Except, instead of needing to build a delivery pipeline, you just have to insert records into an append-only database table.

User recommendation
1. For API consumers
	1. webhooks is suitable for short term event and for workflows that stays OK if webhooks gets dropped (no critical data is involved)
	2. 'events' is more suitable for integration , scenarios that ensures no data should be missing. 
2. For API producers
	1. support these two will creare a kick-ass API for products. 