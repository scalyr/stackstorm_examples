# Sclalyr examples

This automation pack contains examples of integrating Scalyr with broad variety of DevOps tools.
This is a beginning, more sample automations to come. So far:

* `on-scalyr-alert` rule: webhook is configured on Scalyr alert, and, when triggered, starts a workflow`.
* `showcase` workflow is triggered by the rule and does some basic incident automatioon,
    like getting relevant logs from Scalyr, creating a help desk ticket in Zendesk,
    and paging ops team via OpsGenie.
