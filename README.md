# More Summary Fields

Provides additional fields under the [Summary Fields](https://civicrm.org/extensions/summary-fields) framework.

## Requirements

* [Summary Fields](https://civicrm.org/extensions/summary-fields) Extension

## Additional fields

This extension currently provides the following fields:

* CiviContribute: Total Contributions this calendar year (also: renames Summary Fields "Total Contributions this year" to "Total Contributions this fiscal year")
* CiviContribute: Total Contributions last calendar year (also: renames Summary Fields "Total Contributions last year" to "Total Contributions last fiscal year")
* CiviContribute: Total Contributions Calendar Year Before Last (also: renames Summary Fields "Total Contributions Year Before Last" to "Total Contributions Fiscal Year Before Last")
* CiviContribute: Lifetime contributions + soft credits
* CiviContribute: Number of years of contributions
* CiviContribute: Total soft credits this calendar year
* CiviContribute: Total soft credits previous calendar year
* CiviContribute: Total soft credits previous fiscal year
* CiviContribute/Relationship: Related contact contributions this fiscal year
* CiviContribute/Relationship: Related contact contributions this calendar year
* CiviContribute/Relationship: Related contact contributions last fiscal year
* CiviContribute/Relationship: Related contact contributions last calendar year
* CiviContribute/Relationship: Related contact contributions all time
* CiviContribute/Relationship: Combined contact & related contact contributions this fiscal year
* CiviContribute/Relationship: Combined contact & related contact contributions this calendar year
* CiviContribute/Relationship: Combined contact & related contact contributions last fiscal year
* CiviContribute/Relationship: Combined contact & related contact contributions last calendar year
* CiviContribute/Relationship: Combined contact & related contact contributions all time
* CiviEvents: Date of the first attended event
* CiviMail: CiviMail open rate (all time)
* CiviMail: CiviMail open rate (last 12 months)
* CiviMail: CiviMail click-through rate (all time)
* CiviGrant: Total number of grants received
* CiviGrant: Total $ in grants received
* CiviGrant: Grant types received

## Installation
The Summary Fields extension **must** already be installed before installling 
this extension. If they are installed in the reverse order, you'll find that some
of this extension's summary fields will frequently revert to "0". To fix this,
you can take these steps at any time:

1. Disable the "More Summary Fields" extension.
2. Uninstall the "More Summary Fields" extension.
3. Enable the "More Summary Fields" extension.