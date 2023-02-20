# Read Content

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "read_content",
  "detailed_event": "Read Content",
    "action": "<action>",
    "event_data": {
        "page_engagement_type": "<page_engagement_type>"
    },
    "page": "<page>"
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|action|string|The generic action of an event property||||||||
|event_data.page_engagement_type|string|Either 1 minute and 50% scroll or 1 minute and 75% scroll|"1 Minute and 50% Scroll" or "1 Minute and 75% Scroll"|||||||
|page|string|This is the page parameter for the read\_content event specific to UA reporting||||||||




