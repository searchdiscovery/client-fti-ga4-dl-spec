# Carousel Clicks

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "carousel_click",
  "detailed_event": "Carousel Clicks",
    "action": "<action>",
    "event_data": {
        "category": "<category>",
        "link_id": "<link_id>",
        "link_text": "<link_text>",
        "link_type": "<link_type>",
        "link_url": "<link_url>",
        "outbound": <outbound>
    },
    "name": "<name>"
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|action|string|The generic action of an event property||||||||
|event_data.category|string|Optional field that enables you to assign this link a specific category.|radio button, toggle button|||||||
|event_data.link_id|string|Optional field that enables you to assign this link a specific ID.||||||||
|event_data.link_text|string|The full text of the link.||||||||
|event_data.link_type|string|Records the type of link that was clicked. The type here refers to what comes before the :\/\/||||||||
|event_data.link_url|string|The full URL of the link.||||||||
|event_data.outbound|boolean|Does the link point to a different domain?|true, false|||||||
|name|string|The generic name of an event property||||||||

## Attached Notes

<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Fire the code snippet below when a carousel next/prev or radio button is clicked\n\nNote:\nIf the carousel has no name the name should be &ldquo;Carousel 1&rdquo; and so on as the carousels go down the page.\nOn mobile, this event should fire on swipe left/right&quot;}" data-sheets-userformat="{&quot;2&quot;:14849,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0,&quot;14&quot;:{&quot;1&quot;:2,&quot;2&quot;:0},&quot;15&quot;:&quot;Arial&quot;,&quot;16&quot;:11}">Fire the code snippet below when a carousel next/prev or radio button is clicked<br /><br />Note:<br />If the carousel has no name the name should be &ldquo;Carousel 1&rdquo; and so on as the carousels go down the page.<br />On mobile, this event should fire on swipe left/right</span></p>
<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Fire the code snippet below when a carousel next/prev or radio button is clicked\n\nNote:\nIf the carousel has no name the name should be &ldquo;Carousel 1&rdquo; and so on as the carousels go down the page.\nOn mobile, this event should fire on swipe left/right&quot;}" data-sheets-userformat="{&quot;2&quot;:14849,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0,&quot;14&quot;:{&quot;1&quot;:2,&quot;2&quot;:0},&quot;15&quot;:&quot;Arial&quot;,&quot;16&quot;:11}"><img title="Carousel" src="https://github.com/searchdiscovery/client-fti-ga4-dl-spec/blob/main/images/Carousel.png?raw=true" alt="" /></span></p>
