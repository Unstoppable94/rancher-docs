---
title: API
layout: rancher-default
---

## loadBalancerTarget

Collection Test Description

​
### Resource Fields

Field | Type | Create | Update | Default | Notes
---|---|---|---|---|---
description | string | Optional | Yes | - | 
id | int | - | - | - | The unique identifier for the loadBalancerTarget
instanceId | [instance]({{site.baseurl}}/rancher/api/api-resources/instance/) | Optional | - | - | The unique identifier for the associated instance
ipAddress | string | Optional | - | - | The ip address for an external service
loadBalancerId | [loadBalancer]({{site.baseurl}}/rancher/api/api-resources/loadBalancer/) | - | - | - | 
name | string | Optional | Yes | - | 
ports | array[string] | Yes | - | - | 

<br>
Please read more about the [common resource fields]({{site.baseurl}}/rancher/api/common/). 
These fields are read only and applicable to almost every resource. We have segregated them from the list above.
​








​
### Actions

<span class="action">
<span class="header">
remove
<span class="headerright">POST:  <code>${actions.remove}</code></span>
</span>
<div class="action-contents">
To remove the loadBalancerTarget
<br>

<span class="input">
<strong>Input:</strong>This action has no inputs
<br>

<br>
</span>

<span class="output"><strong>Output:</strong> An updated copy of the <a href="/rancher/api/api-resources/loadBalancerTarget/">loadBalancerTarget</a> resource
</span>
</div>
</span>
</span>
</span>

