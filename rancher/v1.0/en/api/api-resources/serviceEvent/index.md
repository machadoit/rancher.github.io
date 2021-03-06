---
title: API
layout: rancher-default-v1.0
version: v1.0
lang: en
---

## serviceEvent



### Resource Fields

Field | Type | Create | Update | Default | Notes
---|---|---|---|---|---
description | string | Optional | Yes | - | 
externalTimestamp | int | - | - | - | 
healthcheckUuid | string | - | - | - | The universal unique identifier of the healthcheck
hostId | [host]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/host/) | - | - | - | The unique identifier for the associated host
id | int | - | - | - | The unique identifier for the serviceEvent
instanceId | [instance]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/instance/) | - | - | - | The unique identifier for the associated instance
name | string | Optional | Yes | - | 
reportedHealth | string | - | - | - | The reported health


Please read more about the [common resource fields]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/common/). 
These fields are read only and applicable to almost every resource. We have segregated them from the list above.








### Actions

<div class="action">
<span class="header">
remove
<span class="headerright">POST:  <code>${actions.remove}</code></span></span>
<div class="action-contents">
To remove the serviceEvent
<br>

<span class="input">
<strong>Input:</strong>This action has no inputs</span>
<br>

<br>


<span class="output"><strong>Output:</strong> An updated copy of the <a href="/rancher/api/api-resources/serviceEvent/">serviceEvent</a> resource</span>
</div>
</div>

