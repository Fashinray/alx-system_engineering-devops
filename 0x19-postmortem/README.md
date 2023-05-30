
https://docs.google.com/document/d/19ecH3WvXvdbcVGJDJ6mwO5G9IKFg_LsmcUBMpHQYiLg/edit?usp=drivesdk






Postmortem: Outage Incident on Web Stack - May 25, 2023


Issue Summary:

Duration: May 25, 2023, 10:00 AM to May 25, 2023, 2:00 PM (UTC-5)

Impact: Slow performance and intermittent service disruptions

Affected Service: Web Application

User Experience: Users experienced slow response times, intermittent errors, and difficulties accessing certain features. Approximately 30% of users were affected.


Timeline:

- 10:15 AM: Issue detected through automated monitoring alerts indicating increased response times.

- 10:20 AM: Engineers on-call received notifications and began investigating the issue.

- 10:30 AM: Initial assumption was that the performance degradation might be due to a high load on the database servers.

- 10:45 AM: Database servers were thoroughly investigated, but no abnormalities were found.

- 11:00 AM: Investigation shifted towards the application server layer, suspecting a misconfiguration or resource bottleneck.

- 11:30 AM: Misleading investigation path taken as engineers focused on optimizing the application server's resource allocation.

- 12:00 PM: The incident was escalated to the backend engineering team for further assistance and expertise.
