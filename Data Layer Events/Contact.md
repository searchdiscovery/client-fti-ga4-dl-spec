# Contact

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "contact",
  "detailed_event": "Contact",
    "action": "<action>",
    "event_data": {
        "contact_action": "<contact_action>",
        "method": "<method>"
    },
    "method": "<method>"
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|action|string|The generic action of an event property||||||||
|event_data.contact_action|string|either "open", "close chat button", "send message", "survey start", "survey submit" or "close call button"|"open", "close chat button", "send message", "survey start", "survey submit", "close call button"|||||||
|event_data.method|string|The site that is tied to the FTI specific "login" event, which is intended to collect event\_data, not user\_data||||||||
|method|string|The site that is tied to the FTI specific "login" event, which is intended to collect event\_data, not user\_data||||||||

## Attached Notes

<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Fire the code snippet below when interacts with chat or call.&quot;}" data-sheets-userformat="{&quot;2&quot;:14849,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0,&quot;14&quot;:{&quot;1&quot;:2,&quot;2&quot;:0},&quot;15&quot;:&quot;Arial&quot;,&quot;16&quot;:11}">Fire the code snippet below when interacts with chat or call.</span></p>
<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Fire the code snippet below when interacts with chat or call.&quot;}" data-sheets-userformat="{&quot;2&quot;:14849,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0,&quot;14&quot;:{&quot;1&quot;:2,&quot;2&quot;:0},&quot;15&quot;:&quot;Arial&quot;,&quot;16&quot;:11}"><img title="Chat or Call" src="&quot;https:/github.com/searchdiscovery/client-fti-ga4-dl-spec/blob/main/images/Chat%20or%20Call" alt="" /></span></p>
