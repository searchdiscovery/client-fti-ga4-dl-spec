# Login Location

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({
  "event": "login_attempt",
  "detailed_event": "Login Location",
    "link_url": "<link_url>",
    "location": "<location>"
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|link_url|string|This will inform the full URL to a downloaded file, if available||||||||
|location|string|This informs where a file download occurs, and is intended to help differentiate between Instant Search downloads or other areas where a download takes place|search|||||||




