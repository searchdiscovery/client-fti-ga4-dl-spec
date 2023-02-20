# Share Click

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "share",
  "detailed_event": "Share Click",
    "event_data": {
        "content_type": "<content_type>",
        "item_id": "<item_id>",
        "method": "<method>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.content_type|string|The content that is actually being shared|"blog article", "financial statement"|||||||
|event_data.item_id|string|Captures the Product Id requested in search criteria.|155, 65588, 987764448|||||||
|event_data.method|string|The site that is tied to the FTI specific "login" event, which is intended to collect event\_data, not user\_data||||||||




