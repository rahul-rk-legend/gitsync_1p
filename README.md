# GitSync

## Integrations
|Name|Description|
|----|-----------|
|CSV|Integration designed around working with CSV files. CSV is a simple file format used to store tabular data, such as a spreadsheet or database.|
|CrowdStrike Falcon|CrowdStrike Falcon is the leader in next-generation endpoint protection, threat intelligence and incident response through cloud-based endpoint protection.|
|FileUtilities|A set of file utility actions created for Google SecOps Community to power up playbook capabilities.|
|Functions|A set of math and data manipulation actions created for Google SecOps Community to power up playbook capabilities.|
|Google Chronicle|Google SecOps enables you to examine the aggregated security information for your enterprise going back for months or longer. Use Google SecOps to search across all of the domains accessed from within your enterprise. To enable the Google API client to communicate with the Backstory API you will need Google Developer Service Account Credential, https://developers.google.com/identity/protocols/OAuth2#serviceaccount.|
|Sample Integration|This is an educational integration designed to showcase the most common design patterns, when working with actions, connectors and jobs.|
|Siemplify|Google SecOps integration package includes all of Google SecOps's internal actions, jobs etc.|
|UrlScanIo|urlscan.io is a service to scan and analyse websites.|
|VirusTotalV3|VirusTotal was founded in 2004 as a free service that analyzes files and URLs for viruses, worms, trojans and other kinds of malicious content. Our goal is to make the internet a safer place through collaboration between members of the antivirus industry, researchers and end users of all kinds. Fortune 500 companies, governments and leading security companies are all part of the VirusTotal community, which has grown to over 500,000 registered users.This integration was created using the 3rd iteration of VT API.|


## Connectors
|Name|Description|Has Mappings|
|----|-----------|------------|
|Google Chronicle - Chronicle Alerts Connector|Pull information about Rule based alerts from Google Chronicle. Note: dynamic list is used for filtering purposes. For all of the details please visit the documentation portal.|True|
|Sample Integration - Simple Connector Example|This is an example of a simple connector. It's integrated with "api.vatcomply.com" service and provides all of the main design ideas necessary to build a stable connector. Dynamic List defines what rates should be returned for a given currency and expects input in the format "EUR" etc.|False|
|VirusTotal - Livehunt Notifications Connector|Pull information about Livehunt notifications and related files from VirusTotal. Note: this connector requires a premium API token. Dynamic list works with "rule_name" parameter.|True|


## Playbooks
|Name|Description|
|----|-----------|
|Playbook 1P Folder 1||
|Playbook Default||
|Playbook Default 1||


## Visual Families
|Name|Description|
|----|-----------|
|Testing Family 1|Testing Family 1|
|Testing Family 2|Testing Family 2|
|Testing Family 3|Testing Family 3|


## Jobs
|Name|Description|
|----|-----------|
|projects/project/locations/location/instances/instance/integrations/GoogleChronicle/jobs/2/jobInstances/8|This job will sync new SOAR alerts with Chronicle SIEM.Note: This job is only supported from Chronicle SOAR version 6.2.30 and higher.|
|projects/project/locations/location/instances/instance/integrations/Siemplify/jobs/6/jobInstances/16|Collect cases and connector logs from Publisher.|

