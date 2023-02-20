# Information Text Box

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "information_text_box",
  "detailed_event": "Information Text Box",
    "event_data": {
        "information_text_box_label": "<information_text_box_label>",
        "information_text_box_name": "<information_text_box_name>"
    },
    "label": "<label>",
    "name": "<name>"
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.information_text_box_label|string|The information text box label||||||||
|event_data.information_text_box_name|string|The information text box name||||||||
|label|string|The generic label of an event property||||||||
|name|string|The generic name of an event property||||||||




