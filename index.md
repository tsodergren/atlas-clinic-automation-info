---
layout: page
title: Atlas Clinic Automation
permalink: /
---

Atlas Clinic Automation is a private, internal application operated by Atlas
Internal Medicine. It connects only to the practice's own QuickBooks Online
company and is not offered to the public.

The current integration performs a limited accounting-data remediation:

- It reads selected QuickBooks deposit and customer references.
- It verifies those records against an Atlas-controlled local audit store.
- With explicit administrator approval, it replaces obsolete patient-specific
  sub-customer references with a generic accounting customer.
- It verifies that deposit dates, accounts, splits, and amounts remain unchanged.

The application requests the QuickBooks Online Accounting permission only. It
does not request QuickBooks Payments or Payroll access.

[Privacy policy](privacy/) · [Internal-use terms](terms/) ·
[Connect or reconnect](connect/) · [Disconnect](disconnected/)

