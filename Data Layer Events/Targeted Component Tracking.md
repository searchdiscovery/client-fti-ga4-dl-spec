# Targeted Component Tracking

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "targeted_component_track",
  "detailed_event": "Targeted Component Tracking",
    "action": "<action>",
    "event_data": {
        "target_component_action": "<target_component_action>",
        "target_component_label": "<target_component_label>"
    },
    "label": "<label>"
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|action|string|The generic action of an event property||||||||
|event_data.target_component_action|string|notes if the interaction was an impression or a click||||||||
|event_data.target_component_label|string|denotes the name of the targeted component that appeared or was clicked on||||||||
|label|string|The generic label of an event property||||||||

## Attached Notes

<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Fire the code snippet below as a user is exposed to and/or clicks on a Targeted component.&quot;}" data-sheets-userformat="{&quot;2&quot;:513,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0}">Fire the code snippet below as a user is exposed to and/or clicks on a Targeted component.</span></p>
<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Fire the code snippet below as a user is exposed to and/or clicks on a Targeted component.&quot;}" data-sheets-userformat="{&quot;2&quot;:513,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0}"><img title="Targeted Component Tracking" src="https://github.com/searchdiscovery/client-fti-ga4-dl-spec/blob/main/images/Targeted%20Component%20Tracking.png?raw=true" alt="" /></span></p>
