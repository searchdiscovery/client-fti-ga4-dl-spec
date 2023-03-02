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

## Attached Notes

<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Add the code snippet below to tables where a user sorts columns so usage of the functionality can be tracked. &quot;}" data-sheets-userformat="{&quot;2&quot;:14849,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0,&quot;14&quot;:{&quot;1&quot;:2,&quot;2&quot;:0},&quot;15&quot;:&quot;Arial&quot;,&quot;16&quot;:11}">Add the code snippet below to tables where a user sorts columns so usage of the functionality can be tracked. </span></p>
<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Add the code snippet below to tables where a user sorts columns so usage of the functionality can be tracked. &quot;}" data-sheets-userformat="{&quot;2&quot;:14849,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0,&quot;14&quot;:{&quot;1&quot;:2,&quot;2&quot;:0},&quot;15&quot;:&quot;Arial&quot;,&quot;16&quot;:11}"><img title="Table Sort" src="https://github.com/searchdiscovery/client-fti-ga4-dl-spec/blob/main/images/Table%20Sort.png?raw=true" alt="" /></span></p>
