---
layout: component
title:  "Test"
subheadline:  "Pick me up"
teaser: "Does this item get picked up?"
categories:
    - TM
tags:
    - TM
header:
    background-color:  "#304558"
---

###Name: Group Lookup  
Description: This custom block component lets you lookup the groups configured in Transact Manager. The client-side composer block talks to a Dynamic Data service (provided in this package) to lookup groups with matching search term.

The search can be done on the Group Name only.

The matching search results will be displayed in an auto-suggest text field and the user can select an entry. The selected grou’ps details will be stored in a hidden XML node which then can be used to drive further form logic.


## Installation Steps - 
1. Import the contents of 'Composer-custom-block-GroupLookup.xml' file into your composer environment. This xml file contains the custom block definition so import it against the organisation of your choice.
2. Import the 'TM-daynamic-data-service-GroupsLookup.zip' into Service Definitions section of Transaction Manager. This zip file contains the definition of ‘Groups Lookup' service that the composer component will call. This service is of type 'Dynamic Data'

## Develop & Test - 
* Once the composer and TM services are imported then open your form.
* You'll find 'TM Group Lookup - Autocomplete textfield' block under 'Transaction Manager' category in composer widget palette.
* Drag and drop this block to your form section and deploy the form to the environment where you imported the supplied Dynamic Data service.
* Type a group name in the text field and matching groups will be shown in the auto-suggest list.
* Select a desired group and save the form.
* The saved form's XML will show you the group name in <SelectedGroup> element
