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




