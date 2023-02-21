# Brightcove Videos

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "videoEvent",
  "detailed_event": "Brightcove Videos",
    "event_data": {
        "media_action": "<media_action>",
        "media_name": "<media_name>",
        "media_provider": "<media_provider>",
        "media_type": "<media_type>",
        "video_name": "<video_name>",
        "video_player": "<video_player>"
    },
    "videoAction": "<videoAction>",
    "videoCategory": "<videoCategory>",
    "videoLabel": "<videoLabel>"
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.media_action|string|This is the GA4 reporting media action parameter||||||||
|event_data.media_name|string|This is the media name for GA4 reporting||||||||
|event_data.media_provider|string|The entity providing the technology housing the media||||||||
|event_data.media_type|string|This is the media type for GA4 reporting||||||||
|event_data.video_name|string|This is the video name, a concatenation of the ID and Title||||||||
|event_data.video_player|string|This is the video player parameter|Brightcove, Vimeo, etc.|||||||
|videoAction|string|This is the video action for UA reporting||||||||
|videoCategory|string|This is the video category for the UA reporting||||||||
|videoLabel|string|This is the video label for UA reporting||||||||




