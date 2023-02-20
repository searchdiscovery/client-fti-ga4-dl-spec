# Notification Alert

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "notification_alert",
  "detailed_event": "Notification Alert",
    "action": "<action>",
    "event_data": {
        "notification_action": "<notification_action>",
        "notification_label": "<notification_label>"
    },
    "label": "<label>"
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|action|string|The generic action of an event property||||||||
|event_data.notification_action|string|This indicates the type of notification activity tracked||||||||
|event_data.notification_label|string|This states if there are “notifications present” or “no notifications”||||||||
|label|string|The generic label of an event property||||||||




