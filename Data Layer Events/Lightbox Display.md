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

## Attached Notes

<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Add the code snippet below such that it executes when a lightbox is displayed.&quot;}" data-sheets-userformat="{&quot;2&quot;:14849,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0,&quot;14&quot;:{&quot;1&quot;:2,&quot;2&quot;:0},&quot;15&quot;:&quot;Arial&quot;,&quot;16&quot;:11}">Add the code snippet below such that it executes when a lightbox is displayed.</span></p>
<p><img title="Lightbox" src="https://github.com/searchdiscovery/client-fti-ga4-dl-spec/blob/main/images/Lightbox.png?raw=true" alt="" /></p>
