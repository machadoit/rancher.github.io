---
title: API
layout: rancher-default-v1.0
version: v1.0
lang: zh
---

## externalHostEvent



### Resource Fields

Field | Type | Create | Update | Default | Notes
---|---|---|---|---|---
deleteHost | boolean | Optional | - | - | 
eventType | string | Optional | - | - | 
externalId | string | - | - | - | 
hostId | [host]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/host/) | Optional | - | - | The unique identifier for the associated host
hostLabel | string | Optional | - | - | 
id | int | - | - | - | The unique identifier for the externalHostEvent
reportedAccountId | [account]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/account/) | - | - | - | 


Please read more about the [common resource fields]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/common/). 
These fields are read only and applicable to almost every resource. We have segregated them from the list above.


### Operations
{::options parse_block_html="true" /}



<div class="action">
<span class="header">
Create
<span class="headerright">POST:  <code>/v1/externalHostEvent</code></span></span>
<div class="action-contents">
{% highlight json %} 
{

	"deleteHost": false,

	"eventType": "string",

	"hostId": "reference[host]",

	"hostLabel": "string"

} 
{% endhighlight %}
</div>
</div>











### Actions

<div class="action">
<span class="header">
remove
<span class="headerright">POST:  <code>${actions.remove}</code></span></span>
<div class="action-contents">
To remove the externalHostEvent
<br>

<span class="input">
<strong>Input:</strong>This action has no inputs</span>
<br>

<br>


<span class="output"><strong>Output:</strong> An updated copy of the <a href="/rancher/api/api-resources/externalEvent/">externalEvent</a> resource</span>
</div>
</div>

