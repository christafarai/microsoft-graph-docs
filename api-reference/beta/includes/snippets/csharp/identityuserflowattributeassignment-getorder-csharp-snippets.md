---
description: "Automatically generated file. DO NOT MODIFY"
---

```csharp

GraphServiceClient graphClient = new GraphServiceClient( authProvider );

var assignmentOrder = await graphClient.Identity.B2cUserFlows["{id}"].UserAttributeAssignments
	.GetOrder()
	.Request()
	.GetAsync();

```