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

## Attached Notes

<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Add the code snippet below to the site when a user logs in and out to identify/note if notifications are present or not. \n\nNote that if notifications will be on the marketing side of the site we&rsquo;ll try to leverage a GTM visibility trigger instead of a data layer event. &quot;}" data-sheets-userformat="{&quot;2&quot;:513,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0}">Add the code snippet below to the site when a user logs in and out to identify/note if notifications are present or not. <br /><br />Note that if notifications will be on the marketing side of the site we&rsquo;ll try to leverage a GTM visibility trigger instead of a data layer event. </span></p>
<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Add the code snippet below to the site when a user logs in and out to identify/note if notifications are present or not. \n\nNote that if notifications will be on the marketing side of the site we&rsquo;ll try to leverage a GTM visibility trigger instead of a data layer event. &quot;}" data-sheets-userformat="{&quot;2&quot;:513,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0}"><img title="Notification Alert Tracking" src="&quot;https:/github.com/searchdiscovery/client-fti-ga4-dl-spec/blob/main/images/Notification%20Alert%20Tracking.png&quot;" alt="" /></span></p>
