# Scroll Depth Tracking

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "scroll_depth",
  "detailed_event": "Scroll Depth Tracking",
    "action": "<action>",
    "event_data": {
        "milestone": "<milestone>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|action|string|The generic action of an event property||||||||
|event_data.milestone|string|The milestone parameter for the scroll depth event|"25", "50", "75"|||||||




