---
title: Released | Common Transit Convention API Roadmap
weight: 2
---


## Released

### Endpoints ready for test in HRMC's sandbox

| **Title** | **Description** | **API** |
|------|-------------|----|
|**Submit an Arrival Notification message (IE007)** |Send an Arrival Notification message to the office of departure| Public API
|**Resubmit an Arrival Notification message (IE007)**|Resend an Arrival Notification message to the office of departure if the first message was rejected| Public API
|**Submit unloading remarks (IE044)** |Send a message to let the office of destination know that the goods have been unloaded|Public API
|**Check user restricted authentication**|Confirm that users have: signed into Government Gateway; enrolled for Economic Operators Registration and Identification (EORI); obtained a valid  EORI number| Public API
|**Retrieve all messages relating to a Movement Arrival**|PULL all messages sent within 21 days of the goods being released relating to an Arrival Movement ID|Public API
|**Retrieve a single Movement Arrival details**| Retrieve a Movement Arrival's status and details| Public API
|**Retrieve a single message** |Use a message ID to PULL a single message|Public API
|**Retrieve all Arrival Notifications for a trader**|PULL all messages sent within 21 days that relate to a particular trader| Public API
