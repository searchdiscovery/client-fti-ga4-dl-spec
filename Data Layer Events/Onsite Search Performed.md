# Onsite Search Performed

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "search",
  "detailed_event": "Onsite Search Performed",
    "event_data": {
        "search_category": "<search_category>",
        "search_num_results": <search_num_results>,
        "search_term": "<search_term>"
    },
    "search_category": "<search_category>",
    "search_num_results": <search_num_results>,
    "search_term": "<search_term>"
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.search_category|string|A predefined list of search categories for FTI's search event|"instant-manager", "instant-fund", "instant-content", "all", "funds", "literature", "pages"|||||||
|event_data.search_num_results|number|The number of results returned||||||||
|event_data.search_term|string|The keyword entered by a user for a search.||||||||
|search_category|string|A predefined list of search categories for the FTI "search" event|"instant-manager", "instant-fund", "instant-content", "all", "funds", "literature", "pages"|||||||
|search_num_results|number|The number of results returned||||||||
|search_term|string|The keyword entered by a user for a search.||||||||




