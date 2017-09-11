---
layout: post
title: Avoding MARGARET
---

Everyone should avoid MARGARET.

![MARGARET]({{ site.url }}/images/StockSnap_9ML7MMR8T5.jpg)

I'm speaking from personal experience here, but not about a double date gone wrong. 

A good few years ago now, we were integrating with a selection of telecommunications networks to offer a brand new service. Some of them were really on the ball, and knocked out a brand new XMLRPC endpoint, some provided SOAP endpoints, all seemed well.

Until we came to the last network, where APIs and automation of processes wasn't really part of their culture. So the conversations happened and we ended up with a solution that sent CSV files back and forth, using SMTP - the CSV would be sent, then returned within a few hours with the status appended to each row.

A bit weird, but not the end of the world. We pulled an email gateway off the shelf and collected up API calls into a spreadsheet, fired it off, then recreated API responses from the results 

There were a few bumps to start with, as there is with any API, times when the CSV didn't come back quite formatted correctly in some error cases. We asked about that and they said they'd talk to the team, and the response came back that MARGARET now knew about it.

That fixed all the bugs and we launched to some success. Everything was good, until higher loads lead to the API taking more than an hour to respond. We added some monitoring and let them know that it was slowing down.

Fast forward another few weeks, and we get an alert from our monitoring that nothing had been processed for 3 days. We got in touch with our contact and they informed us that MARGARET was sick. 

"When do you think MARGARET will be fixed?", we asked. They weren't sure. Margaret was apparently ill with the flu and wouldn't be in work for at least the next week.

Everything came out. Margaret was a nice lady (who recovered fine!) who was opening the CSVs in Excel and manually entering the data into another web UI to apply it. No-one else with the access had the time to take over, so we waited and the alarms resolved themselves that Friday.

Ever since, I've kept an eye out for MARGARETs, and avoided them whenever I could. You *can* have an automated process be manual for a while, and if you're good, no-one outside the team will ever notice. But eventually a microbe, car door, or summer holiday will get in the way, and your non-automation will stop.

So, Avoid MARGARET, she's just not worth it.
