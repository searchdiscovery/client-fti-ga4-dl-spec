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




