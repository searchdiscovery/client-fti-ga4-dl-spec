# Contact Us Link

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "contact_link",
  "detailed_event": "Contact Us Link",
    "event_data": {
        "category": "<category>",
        "link_id": "<link_id>",
        "link_text": "<link_text>",
        "link_type": "<link_type>",
        "link_url": "<link_url>",
        "outbound": <outbound>
    },
    "label": "<label>",
    "method": "<method>"
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
|label|string|The generic label of an event property||||||||
|method|string|The site that is tied to the FTI specific "login" event, which is intended to collect event\_data, not user\_data||||||||

## Attached Notes

<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Add the code snippet below to the click event of email addresses or phone numbers.\n\nNote:  Email addresses that are captured should only be Franklin Templeton email addresses, otherwise if client email addresses are captured this would be a Personally Identifiable Information (PII) issue.&quot;}" data-sheets-userformat="{&quot;2&quot;:513,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0}">Add the code snippet below to the click event of email addresses or phone numbers.<br /><br />Note: Email addresses that are captured should only be Franklin Templeton email addresses, otherwise if client email addresses are captured this would be a Personally Identifiable Information (PII) issue.</span></p>
<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Add the code snippet below to the click event of email addresses or phone numbers.\n\nNote:  Email addresses that are captured should only be Franklin Templeton email addresses, otherwise if client email addresses are captured this would be a Personally Identifiable Information (PII) issue.&quot;}" data-sheets-userformat="{&quot;2&quot;:513,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0}"><img title="Contact Us" src="https://github.com/searchdiscovery/client-fti-ga4-dl-spec/blob/main/images/Contact%20Us.png?raw=true" alt="" /></span></p>
