# Portfolio ID Tracking

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "portfolio_id",
  "detailed_event": "Portfolio ID Tracking",
    "event_data": {
        "portfolio_id": "<portfolio_id>",
        "process": "<process>"
    },
    "portfolio_id": "<portfolio_id>",
    "process": "<process>"
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.portfolio_id|string|This will pull in the ID or IDs that are being populated in the app. When multiple are pulled in, they should be delineated with a pipe.|abc1234|||||||
|event_data.process|string|The delineation of how the portfolio ID is being used\/viewed such as dashboard view \(would include analysis view which takes a user to the dashboard\), new portfolio, comparison, optimize, edit, copy, or delete.|dashboard|||||||
|portfolio_id|string|This will pull in the ID or IDs that are being populated in the app. When multiple are pulled in, they should be delineated with a pipe.|abc1234|||||||
|process|string|The delineation of how the portfolio ID is being used\/viewed such as dashboard view \(would include analysis view which takes a user to the dashboard\), new portfolio, comparison, optimize, edit, copy, or delete.|dashboard|||||||




