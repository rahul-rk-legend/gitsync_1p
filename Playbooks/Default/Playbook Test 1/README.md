# Playbook Test 1




**Enabled:** True

**Version:** 0

**Type:** Playbook

**Priority:** 2

**Playbook Simulator:** False


### Playbook Trigger
**Trigger Type:** All

**Conditions Operator:** And

##### Conditions
|Key|Operator|Value|
|---|--------|-----|
||Equals||


### Involved Steps (Unordered)
|Step Name|Description|Integration|Original Action|
|---------|-----------|-----------|---------------|
|MicrosoftGraphMailDelegated_Send Email_1|Use the Send Email action to send emails from a specific mailbox to an arbitrary list of recipients. This action can send either plain text or HTML-formatted emails. With appropriate permissions, the action can send emails from a mailbox different than the one specified in the integration configuration. This action doesn't run on Google SecOps entities.|MicrosoftGraphMailDelegated|Send Email|
|Siemplify_Change Alert Priority_1|Automatically change the alert priority to the given input. Note: This action is compatible only with Siemplify version 5.6 and higher.|Siemplify|Change Alert Priority|

