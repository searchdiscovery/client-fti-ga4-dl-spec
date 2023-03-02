# On-Page Timer

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "timer",
  "detailed_event": "On-Page Timer",
    "action": "<action>",
    "event_data": {
        "page_timer": "<page_timer>"
    },
    "increment": "<increment>"
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|action|string|The generic action of an event property||||||||
|event_data.page_timer|string|denotes seconds and minutes achieved such as 30, 1, 2, 3, 4, 5||||||||
|increment|string|This is the increment parameter for the contact event|"seconds", "minutes"|||||||

## Attached Notes

<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Fire the code snippet below as a user spends time on the page.&quot;}" data-sheets-userformat="{&quot;2&quot;:513,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0}">Fire the code snippet below as a user spends time on the page.</span></p>
<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Fire the code snippet below as a user spends time on the page.&quot;}" data-sheets-userformat="{&quot;2&quot;:513,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0}"><img title="On-Page Timer" src="https://github.com/searchdiscovery/client-fti-ga4-dl-spec/blob/main/images/On-Page%20Timer.png?raw=true" alt="" /></span></p>
