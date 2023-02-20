# Lightbox Display

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "lightbox_display",
  "detailed_event": "Lightbox Display",
    "action": "<action>",
    "event_data": {
        "lightbox_action": "<lightbox_action>",
        "lightbox_label": "<lightbox_label>"
    },
    "label": "<label>"
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|action|string|The generic action of an event property||||||||
|event_data.lightbox_action|string|The text of the button that resulted in the lightbox appearing||||||||
|event_data.lightbox_label|string|The name of the lightbox||||||||
|label|string|The generic label of an event property||||||||




