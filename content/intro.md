+++
title = 'Introduction'
date = 2024-05-28T13:12:35-07:00
draft = false
weight = 1
+++

#### 4 Types of data analysis

* **Descriptive - What Happened?:** Summarize previous data to understand trends and patterns without providing any predictions or suggestions.

* **Diagnostic - Why did it happen?:** Start to identify connections within patterns mostly using correlation to understand the underlying factors that cause some observation.

* **Predictive - What might happen?:** Using previous data and modeling make a prediction about future events.

* **Prescriptive - What should we do?:** Using predictive insights, model possible scenarios from different actions that you can take and predict the consequences of those different actions.

#### The 5 V's of big data

* **Volume:** How much data is being ingested.
* **Variety:** How diverse are the incoming data types?
* **Velocity:** How fast do we need to process the data (real-time?)?
* **Veracity:** How accurate does the analysis need to be?
* **Value:** How much value can we expect to gain from the data solution?

#### Different types of databases

When databases reach a sufficient size, you can either write efficiently or read efficiently so you need to use specialized schemes depending on your situation.

* **On-Line Transactional Processing (OLTP aka row based):** Used for write-heavy workflows using normalized architecture and cannot be compressed very well.

* **On-Line Analytic Processing (OLAP aka column based):** Used for read-heavy workflows using de-normalized architecture that can be compressed more. Typically handles a lot of aggregation requests.

In practice, you can use both database schemes by taking in data quickly with OLTP and then copying the data at pre-defined intervals to OLAP for analysis processing.

#### Data velocity

* **Scheduled:** Processing occurs after a specific time.
* **Periodic:** Processing occurs after reaching a threshold amount.
* **Near real-time:** Processing occurs in small batches within minutes of hitting the server.
* **Real-time:** Processing occurs in very small batches within milliseconds of hitting the server.

