[![Licensed under CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

# What is this?
A list of email domains for delivery to mobile devices, by sms or mms. Sometimes called email-to-SMS (or email-to-MMS) addresses. Includes mobile and pager networks, current and old domains.

## What are the files?
* The *-ALL* file has every (SMS, MMS, paging) domain I've found to-date (i.e. for scrubbing an existing list)
* The *-WORKING* file has a list of domains that have working MX entry(ies) in DNS, thus they appear to support email delivery (i.e. for preventing inclusion, filtering from forms or imports, etc.)
* The *ipynb* is a Jupyter notebook with code I used to validate the -WORKING domains.

## Why?

For an assortment of projects, I needed to flag these email addresses for exclusion in campaigns. Depending on where you are in the world, sending even solicited messages to these endpoints can get you in-trouble with certain carrier networks. As well, long-form emails sent to these devices may not appear as you intend so preventing their inclusion in your lists, or excluding them from campaigns, can save you headache and eliminates some QA burden.

Provided without warranty.
