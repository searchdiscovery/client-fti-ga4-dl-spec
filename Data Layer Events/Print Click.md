# Print Click

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "printEvent",
  "detailed_event": "Print Click",
    "action": "<action>",
    "event_data": {
        "action": "<action>",
        "category": "<category>",
        "label": "<label>",
        "link_id": "<link_id>",
        "link_text": "<link_text>",
        "link_type": "<link_type>",
        "link_url": "<link_url>",
        "outbound": <outbound>
    },
    "label": "<label>"
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|action|string|The generic action of an event property||||||||
|event_data.action|string|This is the generic action for an event property, found in the event\_data object.||||||||
|event_data.category|string|Optional field that enables you to assign this link a specific category.  This describes the region or component of user interaction.|header navigation, main navigation, footer navigation, utility navigation|||||||
|event_data.label|string|This is the generic label for an event property, found in the event\_data object.||||||||
|event_data.link_id|string|Optional field that enables you to assign this link a specific ID.||||||||
|event_data.link_text|string|The full text of the link.||||||||
|event_data.link_type|string|Records the type of link that was clicked. This is a description of the type of link.|tel, mailto, button, in-line text, opened \(accordion\),  closed \(accordion\), next \(Carousel\), previous \(Carousel\), radio button, toggle button, dropdown, tabs|||||||
|event_data.link_url|string|The full URL of the link.||||||||
|event_data.outbound|boolean|Does the link point to a different domain?|true, false|||||||
|label|string|The generic label of an event property||||||||

## Attached Notes

<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Fire the code snippet below when a print component is interacted with. &quot;}" data-sheets-userformat="{&quot;2&quot;:513,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0}">Fire the code snippet below when a print component is interacted with. </span></p>
<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Fire the code snippet below when a print component is interacted with. &quot;}" data-sheets-userformat="{&quot;2&quot;:513,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0}"><img title="Print" src="https://github.com/searchdiscovery/client-fti-ga4-dl-spec/blob/main/images/Print.png?raw=true" alt="" /></span></p>
