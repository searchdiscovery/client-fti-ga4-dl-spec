# Utility Navigation

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "utility_navigation",
  "detailed_event": "Utility Navigation",
    "event_data": {
        "category": "<category>",
        "link_id": "<link_id>",
        "link_text": "<link_text>",
        "link_type": "<link_type>",
        "link_url": "<link_url>",
        "outbound": <outbound>
    },
    "link_text": "<link_text>",
    "link_url": "<link_url>"
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.category|string|Optional field that enables you to assign this link a specific category.|radio button, toggle button|||||||
|event_data.link_id|string|Optional field that enables you to assign this link a specific ID.||||||||
|event_data.link_text|string|The full text of the link.||||||||
|event_data.link_type|string|Records the type of link that was clicked. The type here refers to what comes before the :\/\/||||||||
|event_data.link_url|string|The full URL of the link.||||||||
|event_data.outbound|boolean|Does the link point to a different domain?|true, false|||||||
|link_text|string|link\_text||||||||
|link_url|string|This will inform the full URL to a downloaded file, if available||||||||

## Attached Notes

<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Add the code snippet below to the click event of the utility links.&quot;}" data-sheets-userformat="{&quot;2&quot;:513,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0}">Add the code snippet below to the click event of the utility links.</span></p>
<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Add the code snippet below to the click event of the utility links.&quot;}" data-sheets-userformat="{&quot;2&quot;:513,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0}"><img title="Utility Click" src="&quot;https:/github.com/searchdiscovery/client-fti-ga4-dl-spec/blob/main/images/Utility%20Click.png&quot;" alt="" /></span></p>
