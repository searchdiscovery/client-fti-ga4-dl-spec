# Table Sort

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "table_sort",
  "detailed_event": "Table Sort",
    "event_data": {
        "table_column": "<table_column>",
        "table_sort": "<table_sort>"
    },
    "label": "<label>",
    "name": "<name>"
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.table_column|string|The table column parameter for the table sort event||||||||
|event_data.table_sort|string|The table sort parameter as a direction, for the table sort event|"ascending", "descending"|||||||
|label|string|The generic label of an event property||||||||
|name|string|The generic name of an event property||||||||




