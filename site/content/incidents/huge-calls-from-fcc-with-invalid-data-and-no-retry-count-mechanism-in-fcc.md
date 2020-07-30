+++
title = "Huge Calls from FCC with Invalid Data and No Retry Count mechanism in FCC"
date = 2020-07-30T15:30:00.000+05:30
severity = "degraded-performance"
affectedsystems = ["APIs", "Vendor Portal", "Discounts Portal", "Interlocks Portal"]
resolved = false
+++

|Action|Time|Status|
|------|----|------|
|Issue First Seen|Wed, Jul 29, 2020, 9:00 AM GMT+5:30|Support Ticket Created|
|Microsoft First Response|Wed, Jul 29, 2020 2:14 PM GMT+5:30|Waiting for RCA from MS|
|TDT Deployed a Hot-Fix|Thu, Jul 30, 2020 1:45 PM GMT+5:30|Service working as expected|
|Microsoft Last Response|Thu, Jul 30, 2020 at 1:54 PM GMT+5:30|Waiting for RCA from MS|



RA Vendors sending invalid data to Cloud Server and server is rejecting it. But FCC is retrying the API with Same data again and again and again. This increases the server load by 30% and server is not able to serve other APIs calls. 

In addition to this, Azure Managed Postgres DB is throwing query timeout error eventhough the resources are under-utilized. A Support ticket(120XXXXXXXXXX46) is Open with Microsoft. 

Progress with Microsoft Ticket will be updated here.

**Thu, Jul 30, 2020 at 1:54 PM GMT+5:30** 
Microsoft requested additional details for further investigation.

**Thu, Jul 30, 2020 at 3:21 PM**
All the requested information is shared with Microsoft(for the 3rd time).
