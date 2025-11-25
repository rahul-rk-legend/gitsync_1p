# Playbook Test 2




**Enabled:** True

**Version:** 1

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
|Siemplify_Case Comment_1|Add a comment to the case the current alert has been grouped to|Siemplify|Case Comment|

### Involved Blocks
|Name|Description|
|----|-----------|
|Block 1|An embedded workflow that can receive inputs and return an output.|
