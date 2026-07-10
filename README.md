# Restaurant-order-automation

## 🎥 Demo Video
[Watch the walkthrough](https://youtu.be/zdw2hmD_XLk)

## Problem
Restaurant order intake relied on manual relay between customer form submissions and kitchen/staff notifications, creating delays and providing no visibility into KPIs such as confirmation speed, order volume, or delivery-time demand. There was no automated way to track how quickly orders were being confirmed or to surface trends in customer behavior.

## Approach
Built an end-to-end automation pipeline using *Make.com* that connects:
- *Google Forms* → captures customer order submissions
- *Google Sheets* → stores raw order data as the single source of truth
- *Slack* → sends real-time order notifications to staff
- *Gmail* → sends automated order confirmations to customers

On top of the raw data, built a two-sheet *Excel KPI dashboard* (Raw Orders + KPI Summary with charts) to track confirmation delays, order volume, and delivery-window demand — turning raw submissions into actionable business metrics.

## Result
- Eliminated manual order relay, reducing staff workload and human error
- Automated KPI tracking surfaced a headline metric of* ~3.2-minute average confirmation delay* (calculated from clean, realistic order data)
- Created a reusable dashboard template that separates true fulfillment speed from customer-requested delivery windows — a distinction that matters for accurate reporting

## Tools Used
Make.com · Google Forms · Google Sheets · Slack · Gmail · Excel

## Skills Demonstrated
Workflow automation · KPI design · Data pipeline architecture · Excel dashboarding · Business process improvement
