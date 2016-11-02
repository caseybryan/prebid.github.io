---
layout: bidder
title: RubiconLite
description: Prebid Rubicon Project Lite Bidder Adaptor

top_nav_section: dev_docs
nav_section: reference

hide: true

biddercode: rubiconlite

biddercode_longer_than_12: false

---



### Note:
The Rubicon Project Fastlane adapter requires setup and approval from the Rubicon Project team, even for existing Rubicon Project publishers. Please reach out to your account team or globalsupport@rubiconproject.com for more information and to enable using this adapter.

### bid params

{: .table .table-bordered .table-striped }
| Name | Version | Scope | Description | Example |
| :--- | :------ | :---- | :---------- | :------ |
| `accountId` | 0.13.1 | required | The publisher account ID | `"4934"` |
| `siteId` | 0.13.1 | required | The site ID | `"13945"` |
| `zoneId` | 0.13.1 | required | The zone ID | `"23948"` |
| `sizes` | 0.13.1 | optional | Array of Rubicon Project size IDs. If not specified, the system will try to convert from bid.sizes. | `[15]` |
| `keywords` | 0.13.1 | optional | Array of page-specific keywords. May be referenced in Rubicon Project reports. | `["travel", "tourism"]` |
| `inventory` | 0.13.1 | optional | An object defining arbitrary key-value pairs concerning the page for use in targeting. | `{"rating":"5-star", "prodtype":"tech"}` |
| `visitor` | 0.13.1 | optional | An object defining arbitrary key-value pairs concerning the visitor for use in targeting. | `{"ucat":"new", "search":"iphone"}` |
| `position` | 0.13.1 | optional | Set the page position. Valid values are "atf" and "btf". | `"atf"` |

