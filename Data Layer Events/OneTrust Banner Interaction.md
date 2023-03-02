# OneTrust Banner Interaction

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "onetrust_interaction",
  "detailed_event": "OneTrust Banner Interaction",
    "event_data": {
        "optanon_action": "<optanon_action>",
        "optanon_category": "<optanon_category>",
        "optanon_label": "<optanon_label>"
    },
    "optanonAction": "<optanonAction>",
    "optanonCategory": "<optanonCategory>",
    "optanonLabel": "<optanonLabel>"
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.optanon_action|string|Cookie Preference Banner||||||||
|event_data.optanon_category|string|The consent category \(ie. OneTrust Cookie Consent\)||||||||
|event_data.optanon_label|string|The name of the item clicked||||||||
|optanonAction|string|The Cookie Preference Banner|Cookie Preference Banner|||||||
|optanonCategory|string|OneTrust Cookie Consent|OneTrust Cookie Consent|||||||
|optanonLabel|string|The name of the item clicked|“Accept”|||||||

## Attached Notes

<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Add the code snippet below on click events where the OneTrust privacy banner is engaged with.&quot;}" data-sheets-userformat="{&quot;2&quot;:513,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0}">Add the code snippet below on click events where the OneTrust privacy banner is engaged with.</span></p>
<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Add the code snippet below on click events where the OneTrust privacy banner is engaged with.&quot;}" data-sheets-userformat="{&quot;2&quot;:513,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0}"><img title="OneTrust Banner Interaction" src="&quot;https:/github.com/searchdiscovery/client-fti-ga4-dl-spec/blob/main/images/OneTrust%20Banner%20interaction.png&quot;" alt="" /></span></p>
