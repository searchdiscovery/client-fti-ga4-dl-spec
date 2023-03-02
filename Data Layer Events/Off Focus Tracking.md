# Off Focus Tracking

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "form_focus",
  "detailed_event": "Off Focus Tracking",
    "event_data": {
        "form_focus_label": "<form_focus_label>",
        "form_focus_name": "<form_focus_name>"
    },
    "label": "<label>",
    "name": "<name>"
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.form_focus_label|string|This denotes the scenario, menu, flow where the event pertains to such as “personal details”||||||||
|event_data.form_focus_name|string|This indicates the name of the field where focus was removed from||||||||
|label|string|The generic label of an event property||||||||
|name|string|The generic name of an event property||||||||

## Attached Notes

<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Add the code snippet below on click events where a users focus is removed from a form field. &quot;}" data-sheets-userformat="{&quot;2&quot;:513,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0}">Add the code snippet below on click events where a users focus is removed from a form field. </span></p>
<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Add the code snippet below on click events where a users focus is removed from a form field. &quot;}" data-sheets-userformat="{&quot;2&quot;:513,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0}"><img title="Off Focus Tracking" src="&quot;https:/github.com/searchdiscovery/client-fti-ga4-dl-spec/blob/main/images/Off%20Focus%20Tracking.png&quot;" alt="" /></span></p>
