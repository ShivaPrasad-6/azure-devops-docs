---
ms.topic: include
---


## Post-upgrade customizations to make manually 

The upgrade makes a best-effort attempt to reconcile the system process and the customizations made to the Hosted XML process. After you upgrade, you'll want to review the inherited process and reapply customizations manually. 

- [Create a test project](../work/upgrade-hosted-to-inherited.md#verify): Use to verify the customizations preserved or reapplied to a process
- [Update the default value for any field](../work/customize-process-field.md): define any default values you had previously defined
- [Workflow states](../work/customize-process-workflow.md): verify the mapping of states to workflow state categories 
- [Custom rules](../work/custom-rules.md): You can recreate select rules as needed. Note, however, there is not a one-to-one mapping of rules defined in a Hosted XML process model and those for an inherited process. Specifically:   
	- Some rules are already defined in the system process or auto-generated (e.g. certain system fields such as Changed By, Change Date, Closed By, Closed Date)  
	- Some rules are now specified as field attributes (default, required)  
- [Disable work item types](../work/customize-process-work-item-type.md#enable-disable)
- [Hide inherited fields or controls](../work/customize-process-field.md#show-hide-or-remove-a-field)
- [Custom controls](../work/custom-controls-process.md): verify that custom controls are applied as expected; disable or hide unwanted [groups or page extensions](../work/custom-controls-process.md#group-level-and-page-level-contributions).