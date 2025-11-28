# GitSync

## Integrations
|Name|Description|
|----|-----------|
|CSV|Integration designed around working with CSV files. CSV is a simple file format used to store tabular data, such as a spreadsheet or database.|
|CrowdStrike Falcon|CrowdStrike Falcon is the leader in next-generation endpoint protection, threat intelligence and incident response through cloud-based endpoint protection.|
|FileUtilities|A set of file utility actions created for Google SecOps Community to power up playbook capabilities.|
|Functions|A set of math and data manipulation actions created for Google SecOps Community to power up playbook capabilities.|
|Google Chronicle|Google SecOps enables you to examine the aggregated security information for your enterprise going back for months or longer. Use Google SecOps to search across all of the domains accessed from within your enterprise. To enable the Google API client to communicate with the Backstory API you will need Google Developer Service Account Credential, https://developers.google.com/identity/protocols/OAuth2#serviceaccount.|
|Microsoft Graph Mail Delegated|This integration version uses Delegated Authentication in Microsoft 365 and requires interactive login of the user on behalf of which integration should communicate with Microsoft 365. To configure this integration, provide all parameters except for Refresh Token, and save the integration configuration, then run “Get Authorization” and “Generate Token” actions to get the token and then provide it in integration configuration to finish the process. Microsoft 365 and Office 365 deliver the power of cloud productivity to businesses of all sizes, helping save time, money, and free up valued resources. The Microsoft 365 and Office 365 plans combine the familiar Microsoft Office desktop suite with cloud-based versions of Microsoft's next-generation communications and collaboration services (including Office for the web, Microsoft Exchange Online, Microsoft Teams, and Microsoft SharePoint Online) to help users be productive from virtually anywhere through the Internet. This integration uses Microsoft Graph Mail API to communicate with Microsoft 365 and Office 365 services.|
|Sample Integration|This is an educational integration designed to showcase the most common design patterns, when working with actions, connectors and jobs.|
|Siemplify|Google SecOps integration package includes all of Google SecOps's internal actions, jobs etc.|
|UrlScanIo|urlscan.io is a service to scan and analyse websites.|
|VirusTotalV3|VirusTotal was founded in 2004 as a free service that analyzes files and URLs for viruses, worms, trojans and other kinds of malicious content. Our goal is to make the internet a safer place through collaboration between members of the antivirus industry, researchers and end users of all kinds. Fortune 500 companies, governments and leading security companies are all part of the VirusTotal community, which has grown to over 500,000 registered users.This integration was created using the 3rd iteration of VT API.|


## Playbooks
|Name|Description|
|----|-----------|
|Playbook Test 1||
|Playbook Test 2||
|Playbook Test 3||
|Playbook Test 4||


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
|projects/project/locations/location/instances/instance/integrations/MicrosoftGraphMailDelegated/jobs/9/jobInstances/10|Token renewal job should be used to periodically update the refresh token configured for the integration. By default, the refresh token expires every 90 days, making integration unusable upon expiration. It is recommended to run this job every 7 or 14 days to make sure that refresh token will be up to date.|
|projects/project/locations/location/instances/instance/integrations/Siemplify/jobs/6/jobInstances/16|Collect cases and connector logs from Publisher.|

