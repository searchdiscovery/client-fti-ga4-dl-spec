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

## Attached Notes

<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Add the code snippet below to forms so that when the form is submitted we can effectively track the process.&quot;}" data-sheets-userformat="{&quot;2&quot;:14849,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0,&quot;14&quot;:{&quot;1&quot;:2,&quot;2&quot;:0},&quot;15&quot;:&quot;Arial&quot;,&quot;16&quot;:11}">Add the code snippet below to forms so that when the form is submitted we can effectively track the process.</span></p>
<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Add the code snippet below to forms so that when the form is submitted we can effectively track the process.&quot;}" data-sheets-userformat="{&quot;2&quot;:14849,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0,&quot;14&quot;:{&quot;1&quot;:2,&quot;2&quot;:0},&quot;15&quot;:&quot;Arial&quot;,&quot;16&quot;:11}"><img title="Form Submission" src="&quot;https:/github.com/searchdiscovery/client-fti-ga4-dl-spec/blob/main/images/Form%20Submission.png&quot;" alt="" /></span></p>
