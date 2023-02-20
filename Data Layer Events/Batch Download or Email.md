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




