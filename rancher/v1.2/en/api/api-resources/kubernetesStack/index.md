---
title: API
layout: rancher-api-default
version: v1.2
lang: en
---

## kubernetesStack





### Resource Fields

Field | Type | Required | Default | Description
---|---|---|---|---
description | string | false |  | 
environment | map[string] | false |  | 
externalId | string | false |  | 
healthState | string | false |  | 
id | int | false |  | The unique identifier for the kubernetesStack
name | string | true |  | 
namespace | string | true |  | 
previousEnvironment | map[string] | false |  | 
previousExternalId | string | false |  | 
templates | map[string] | true |  | 

