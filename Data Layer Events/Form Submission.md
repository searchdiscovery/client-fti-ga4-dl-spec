# Form Submission

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "form_submit",
  "detailed_event": "Form Submission",
    "action": "<action>",
    "event_data": {
        "form_name": "<form_name>",
        "form_step": "<form_step>",
        "link_text": "<link_text>"
    },
    "label": "<label>",
    "name": "<name>"
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|action|string|The generic action of an event property||||||||
|event_data.form_name|string|This identifies the name of the form|“Register,” “Sign Up” etc.|||||||
|event_data.form_step|string|denotes the step that the user is on in a multi step flow|“Step 1: Buy-Instructions”, etc|||||||
|event_data.link_text|string|The full text of the link.||||||||
|label|string|The generic label of an event property||||||||
|name|string|The generic name of an event property||||||||




