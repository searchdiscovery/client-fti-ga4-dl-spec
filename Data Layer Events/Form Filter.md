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




