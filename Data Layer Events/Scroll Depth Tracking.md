# Scroll Depth Tracking

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "scroll_depth",
  "detailed_event": "Scroll Depth Tracking",
    "action": "<action>",
    "event_data": {
        "milestone": "<milestone>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|action|string|The generic action of an event property||||||||
|event_data.milestone|string|The milestone parameter for the scroll depth event|"25", "50", "75"|||||||

## Attached Notes

<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Fire the code snippet below as a user scrolls down the page in 25% increments.\n\nNotes: Each threshold should only fire once per page. &quot;}" data-sheets-userformat="{&quot;2&quot;:513,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0}">Fire the code snippet below as a user scrolls down the page in 25% increments.<br /><br />Notes: Each threshold should only fire once per page. </span></p>
<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Fire the code snippet below as a user scrolls down the page in 25% increments.\n\nNotes: Each threshold should only fire once per page. &quot;}" data-sheets-userformat="{&quot;2&quot;:513,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0}"><img title="Scroll Depth Tracking" src="&quot;https:/github.com/searchdiscovery/client-fti-ga4-dl-spec/blob/main/images/Scroll%20Depth%20Tracking.png&quot;" alt="" /></span></p>
