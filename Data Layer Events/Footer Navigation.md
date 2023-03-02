# Footer Navigation

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "footer_navigation",
  "detailed_event": "Footer Navigation",
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

<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Add the code snippet below to the click event of footer links.&quot;}" data-sheets-userformat="{&quot;2&quot;:14849,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0,&quot;14&quot;:{&quot;1&quot;:2,&quot;2&quot;:0},&quot;15&quot;:&quot;Arial&quot;,&quot;16&quot;:11}">Add the code snippet below to the click event of footer links.</span></p>
<p><img title="Footer Navigation" src="https://github.com/searchdiscovery/client-fti-ga4-dl-spec/blob/main/images/Footer%20Navigation.png?raw=true" alt="" /></p>
