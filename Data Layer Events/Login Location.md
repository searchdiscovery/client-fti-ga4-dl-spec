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




