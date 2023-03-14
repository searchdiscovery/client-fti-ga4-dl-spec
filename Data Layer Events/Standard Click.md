# Standard Click

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "click",
  "detailed_event": "Standard Click",
    "event_data": {
        "category": "<category>",
        "link_id": "<link_id>",
        "link_text": "<link_text>",
        "link_type": "<link_type>",
        "link_url": "<link_url>",
        "outbound": <outbound>
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.category|string|Optional field that enables you to assign this link a specific category.  This describes the region or component of user interaction.|header navigation, main navigation, footer navigation, utility navigation|||||||
|event_data.link_id|string|Optional field that enables you to assign this link a specific ID.||||||||
|event_data.link_text|string|The full text of the link.||||||||
|event_data.link_type|string|Records the type of link that was clicked. This is a description of the type of link.|tel, mailto, button, in-line text, opened \(accordion\),  closed \(accordion\), next \(Carousel\), previous \(Carousel\), radio button, toggle button, dropdown, tabs|||||||
|event_data.link_url|string|The full URL of the link.||||||||
|event_data.outbound|boolean|Does the link point to a different domain?|true, false|||||||




