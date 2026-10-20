# Linux Fundamentals

Lab: TryHackMe, Linux Fundamentals 2 and 3
Date: 20th Oct 2026

## What I learned
- SQL injection: “SQL injection happens when user input becomes part of a query. The fix is parameterized queries plus a least-privilege database account.”
- SSRF: “SSRF lets an attacker make the server send requests for them. On AWS it can steal instance credentials from the metadata service, which is why IMDSv2 and egress controls matter.”
- S3 misconfiguration: “Most S3 breaches aren’t hacks but misconfigurations, such as public buckets. Block Public Access and least-privilege bucket policies prevent them.”

## Security angle
- Why file permissions matter:
- How attackers use cron:
- Why logs matter for defenders:

## Interview one-liner

Attackers often use cron jobs to stay in a system after a break-in, so checking crontabs is a basic step in incident response.
