# Calendar Date Selection

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "date_selection",
  "detailed_event": "Calendar Date Selection",
    "action": "<action>",
    "event_data": {
        "date_type": "<date_type>",
        "date_value": "<date_value>"
    },
    "label": "<label>"
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|action|string|The generic action of an event property||||||||
|event_data.date_type|string|the type of date range functionality interacted with such as range, start date, end date etc|date range, start date, end date|||||||
|event_data.date_value|string|the dates or range of dates selected||||||||
|label|string|The generic label of an event property||||||||

## Attached Notes

<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Add the code snippet below so that it executes when a date range selector is interacted with.&quot;}" data-sheets-userformat="{&quot;2&quot;:14849,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0,&quot;14&quot;:{&quot;1&quot;:2,&quot;2&quot;:0},&quot;15&quot;:&quot;Arial&quot;,&quot;16&quot;:11}">Add the code snippet below so that it executes when a date range selector is interacted with.</span></p>
<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Add the code snippet below so that it executes when a date range selector is interacted with.&quot;}" data-sheets-userformat="{&quot;2&quot;:14849,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0,&quot;14&quot;:{&quot;1&quot;:2,&quot;2&quot;:0},&quot;15&quot;:&quot;Arial&quot;,&quot;16&quot;:11}"><img title="Calendar Date Selection" src="https://github.com/searchdiscovery/client-fti-ga4-dl-spec/blob/main/images/Calendar%20Date%20Selection.png" alt="" /></span></p>
