# Read Content

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "read_content",
  "detailed_event": "Read Content",
    "action": "<action>",
    "event_data": {
        "page_engagement_type": "<page_engagement_type>"
    },
    "page": "<page>"
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|action|string|The generic action of an event property||||||||
|event_data.page_engagement_type|string|Either 1 minute and 50% scroll or 1 minute and 75% scroll|"1 Minute and 50% Scroll" or "1 Minute and 75% Scroll"|||||||
|page|string|This is the page parameter for the read\_content event specific to UA reporting||||||||

## Attached Notes

<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Fire the code snippet below when a combination of time on page and scroll depth has been achieved. Specifically, 1 minute on page and 50% scrolled and 1 minute on page and 75% scrolled.&quot;}" data-sheets-userformat="{&quot;2&quot;:14849,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0,&quot;14&quot;:{&quot;1&quot;:2,&quot;2&quot;:0},&quot;15&quot;:&quot;Arial&quot;,&quot;16&quot;:11}">Fire the code snippet below when a combination of time on page and scroll depth has been achieved. Specifically, 1 minute on page and 50% scrolled and 1 minute on page and 75% scrolled.</span></p>
<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Fire the code snippet below when a combination of time on page and scroll depth has been achieved. Specifically, 1 minute on page and 50% scrolled and 1 minute on page and 75% scrolled.&quot;}" data-sheets-userformat="{&quot;2&quot;:14849,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0,&quot;14&quot;:{&quot;1&quot;:2,&quot;2&quot;:0},&quot;15&quot;:&quot;Arial&quot;,&quot;16&quot;:11}"><img title="Read Content" src="https://github.com/searchdiscovery/client-fti-ga4-dl-spec/blob/main/images/Read%20Content.png?raw=true" alt="" /></span></p>
