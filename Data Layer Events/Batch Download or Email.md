# Batch Download or Email

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "batch_files",
  "detailed_event": "Batch Download or Email",
    "action": "<action>",
    "event_data": {
        "cart_action": "<cart_action>",
        "number_files": <number_files>
    },
    "number_files": <number_files>
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|action|string|The generic action of an event property||||||||
|event_data.cart_action|string|The action the user took.|"Add to Cart", "Download from Cart", "Email from Cart", "Direct Mail"|||||||
|event_data.number_files|number|The number of selected documents in the batch||||||||
|number_files|number|The number of selected documents in the batch||||||||

## Attached Notes

<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Fire the code snippet below when the user downloads or emails the files&quot;}" data-sheets-userformat="{&quot;2&quot;:14849,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0,&quot;14&quot;:{&quot;1&quot;:2,&quot;2&quot;:0},&quot;15&quot;:&quot;Arial&quot;,&quot;16&quot;:11}">Fire the code snippet below when the user downloads or emails the files</span></p>
<p><img title="Batch Download or Email" src="https://github.com/searchdiscovery/client-fti-ga4-dl-spec/blob/main/images/Batch%20Download%20or%20Email.png?raw=true" alt="" /><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Fire the code snippet below when the user downloads or emails the files&quot;}" data-sheets-userformat="{&quot;2&quot;:14849,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0,&quot;14&quot;:{&quot;1&quot;:2,&quot;2&quot;:0},&quot;15&quot;:&quot;Arial&quot;,&quot;16&quot;:11}"><img title="Batch Download Email" src="https:/github.com/searchdiscovery/client-fti-ga4-dl-spec/blob/main/images/Batch%20Download%20or%20Email.png?raw=true" alt="" /></span></p>
