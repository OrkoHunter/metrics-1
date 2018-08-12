---
layout: monthly-metrics-v0.1
title: Metrics report for twitterdev/twitter-realtime-voting | MONTHLY-2018-08-12 | 2018-08-12
permalink: /twitterdev/twitter-realtime-voting/MONTHLY/

owner: twitterdev
repo: twitter-realtime-voting
reportID: MONTHLY-2018-08-12
datestampThisMonth: 2018-08-12
datestampLastMonth: 2018-07-13
---

<table style="width: 100%">
    <tr>
        <th>Metric</th>
        <th>This Month</th>
        <th>Last Month</th>
        <th>+/-</th>
    </tr>
    {% for item in site.data["twitterdev"]["twitter-realtime-voting"]["MONTHLY-2018-08-12"]["data"] %}
    <tr>
        <th>{{ item[0] }}</th>
        <th>{{ item[1]["latest"] }}</th>
        <th>{{ item[1]["previous"] }}</th>
        <th>{{ item[1]["diff"] }}</th>
    </tr>
    {% endfor %}
</table>