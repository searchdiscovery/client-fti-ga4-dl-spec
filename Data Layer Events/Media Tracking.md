# Media Tracking

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "media_engagement",
  "detailed_event": "Media Tracking",
    "action": "<action>",
    "event_data": {
        "media_action": "<media_action>",
        "media_name": "<media_name>",
        "media_provider": "<media_provider>",
        "media_type": "<media_type>"
    },
    "media_provider": "<media_provider>",
    "name": "<name>",
    "type": "<type>"
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|action|string|The generic action of an event property||||||||
|event_data.media_action|string|This is the GA4 reporting media action parameter||||||||
|event_data.media_name|string|This is the media name for GA4 reporting||||||||
|event_data.media_provider|string|The entity providing the technology housing the media||||||||
|event_data.media_type|string|This is the media type for GA4 reporting||||||||
|media_provider|string|The media provider||||||||
|name|string|The generic name of an event property||||||||
|type|string|The type of callout|"card", "billboard", "banner"|||||||




