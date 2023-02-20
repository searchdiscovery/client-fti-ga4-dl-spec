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




