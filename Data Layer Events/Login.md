# Login

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "login",
  "detailed_event": "Login",
    "event_data": {
        "method": "<method>",
        "name": "<name>"
    },
    "method": "<method>",
    "name": "<name>"
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.method|string|The site that is tied to the FTI specific "login" event, which is intended to collect event\_data, not user\_data||||||||
|event_data.name|string|This is the generic name for an event property, found in the event\_data object.||||||||
|method|string|The site that is tied to the FTI specific "login" event, which is intended to collect event\_data, not user\_data||||||||
|name|string|The generic name of an event property||||||||

## Attached Notes

<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Fire the code snippet below such that it executes in the following cases:\nAfter successful form validation (login)\nWhen login failed (login fail)\nRe-authentication\nRe-authentication fail&quot;}" data-sheets-userformat="{&quot;2&quot;:513,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0}">Fire the code snippet below such that it executes in the following cases:<br /></span></p>
<ul>
<li><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Fire the code snippet below such that it executes in the following cases:\nAfter successful form validation (login)\nWhen login failed (login fail)\nRe-authentication\nRe-authentication fail&quot;}" data-sheets-userformat="{&quot;2&quot;:513,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0}">After successful form validation (login) </span></li>
<li><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Fire the code snippet below such that it executes in the following cases:\nAfter successful form validation (login)\nWhen login failed (login fail)\nRe-authentication\nRe-authentication fail&quot;}" data-sheets-userformat="{&quot;2&quot;:513,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0}">When login failed (login fail) </span></li>
<li><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Fire the code snippet below such that it executes in the following cases:\nAfter successful form validation (login)\nWhen login failed (login fail)\nRe-authentication\nRe-authentication fail&quot;}" data-sheets-userformat="{&quot;2&quot;:513,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0}">Re-authentication </span></li>
<li><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Fire the code snippet below such that it executes in the following cases:\nAfter successful form validation (login)\nWhen login failed (login fail)\nRe-authentication\nRe-authentication fail&quot;}" data-sheets-userformat="{&quot;2&quot;:513,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0}">Re-authentication fail</span></li>
</ul>
