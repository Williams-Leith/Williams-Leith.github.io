---
title: What we're developing now | Common Transit Convention API Roadmap
weight: 3
---

## What we're working on now

We will update these and release them as soon as they are ready. We expect this to be in the next few weeks.

### Key milestones

| **Project** |**Description** |**Dates**|
|------|-------------|----|
|**Test Support API**| You will be able to place CTC test messages as if they were from the NCTS. It is for use with HMRC’s sandbox environment only. Check out [Test Support API specifications](https://developer.service.hmrc.gov.uk/api-documentation/docs/api/service/common-transit-convention-traders/1.0)|September 2020|
|**Complete departures endpoints**| We will have all the departures endpoints ready|September 2020 |

### Features

|**Title**|**Description**|**API**|
|----|-----------|-----|
|**Submit  a Departure Declaration message (IE015)** |Submit a Departure Declaration message so a trader can start the departure process| Public API
|**Retrieve a single Movement Departure details**| Retrieve a Movement Departure's status and details| Public API
|**Submit a Request for Release message (IE054)**|Submit a Release Request so the trader can move goods| Public API|
|**Retrieve all messages relating to a Movement Departure**|PULL all messages sent within 21 days relating to a Movement Departure ID | Public API|
|**Submit a Request of Release message (IE054)**| Send a message so the trader can start moving goods | Public API
|**Retrieve a single Departure message** |Use a message ID to PULL a single message| Public API|
|**Test scenario for IE928**| Test Declaration received message| Test Support API|





Although some endpoints will not be ready for the sandbox environment, you will be able to see them on [CTC Traders API specifications](https://developer.service.hmrc.gov.uk/api-documentation/docs/api/service/common-transit-convention-traders/1.0)
