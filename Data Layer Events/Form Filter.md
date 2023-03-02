# Form Filter

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "form_filter",
  "detailed_event": "Form Filter",
    "event_data": {
        "filter_type": "<filter_type>",
        "filter_value": "<filter_value>"
    },
    "label": "<label>",
    "name": "<name>"
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.filter_type|string|The type parameter for a filter event||||||||
|event_data.filter_value|string|The value parameter for a filter.||||||||
|label|string|The generic label of an event property||||||||
|name|string|The generic name of an event property||||||||

## Attached Notes

<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Add the code snippet below such that it executes onchange event filter fields.\n\nNote: \nFor text filter fields, it's recommended to a delay the event until the user finishes typing, to avoid sending too many events while the user hasn't finished typing.&quot;}" data-sheets-userformat="{&quot;2&quot;:513,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0}">Add the code snippet below such that it executes onchange event filter fields.<br /><br />Note: <br />For text filter fields, it's recommended to a delay the event until the user finishes typing, to avoid sending too many events while the user hasn't finished typing.</span></p>
<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Add the code snippet below such that it executes onchange event filter fields.\n\nNote: \nFor text filter fields, it's recommended to a delay the event until the user finishes typing, to avoid sending too many events while the user hasn't finished typing.&quot;}" data-sheets-userformat="{&quot;2&quot;:513,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0}"><img title="Form Filter" src="https://github.com/searchdiscovery/client-fti-ga4-dl-spec/blob/main/images/Form%20Filter.png?raw=true" alt="" /></span></p>
