+++
title = "Huge Calls from FCC with Invalid Data and No Retry Count mechanism in FCC"
date = 2020-07-30T15:30:00.000+05:30
severity = "partial-outage"
affectedsystems = ["APIs", "Vendor Portal", "Discounts Portal", "Interlocks Portal"]
resolved = false
+++
RA Vendors sending invalid data to Cloud Server and server is rejecting it. But FCC is retrying the API with Same data again and again and again. This increases the server load by 30% and server is not able to serve other APIs calls. 

In addition to this, Azure Managed Postgres DB is throwing query timeout error eventhough the resources are under-utilized. A Support ticket is Open with Microsoft. ID :: 120072923001646

Progress with Microsoft Ticket will be updated here.
