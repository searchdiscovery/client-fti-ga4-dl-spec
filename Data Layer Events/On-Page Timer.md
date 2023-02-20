# On-Page Timer

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "timer",
  "detailed_event": "On-Page Timer",
    "action": "<action>",
    "event_data": {
        "page_timer": "<page_timer>"
    },
    "increment": "<increment>"
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|action|string|The generic action of an event property||||||||
|event_data.page_timer|string|denotes seconds and minutes achieved such as 30, 1, 2, 3, 4, 5||||||||
|increment|string|This is the increment parameter for the contact event|"seconds", "minutes"|||||||




