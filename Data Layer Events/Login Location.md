# Login Location

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "login_attempt",
  "detailed_event": "Login Location",
    "event_data": {
        "link_url": "<link_url>",
        "location": "<location>"
    },
    "link_url": "<link_url>",
    "location": "<location>"
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.link_url|string|The full URL of the link.||||||||
|event_data.location|string|The location on a page where a downloadable file is found||||||||
|link_url|string|This will inform the full URL to a downloaded file, if available||||||||
|location|string|This informs where a file download occurs, and is intended to help differentiate between Instant Search downloads or other areas where a download takes place|search|||||||

## Attached Notes

<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Fire the code snippet below such that it executes when user attempts to sign in.&quot;}" data-sheets-userformat="{&quot;2&quot;:14849,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0,&quot;14&quot;:{&quot;1&quot;:2,&quot;2&quot;:0},&quot;15&quot;:&quot;Arial&quot;,&quot;16&quot;:11}">Fire the code snippet below such that it executes when user attempts to sign in.</span></p>
<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Fire the code snippet below such that it executes when user attempts to sign in.&quot;}" data-sheets-userformat="{&quot;2&quot;:14849,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0,&quot;14&quot;:{&quot;1&quot;:2,&quot;2&quot;:0},&quot;15&quot;:&quot;Arial&quot;,&quot;16&quot;:11}"><img title="User Signed In" src="https://github.com/searchdiscovery/client-fti-ga4-dl-spec/blob/main/images/User%20Signed%20In.png?raw=true" alt="" /></span></p>
