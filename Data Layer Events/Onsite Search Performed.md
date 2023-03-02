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

## Attached Notes

<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Fire the code snippet below when Instant Display results appears&quot;}" data-sheets-userformat="{&quot;2&quot;:513,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0}">Fire the code snippet below when Instant Display results appears</span></p>
<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Fire the code snippet below when Instant Display results appears&quot;}" data-sheets-userformat="{&quot;2&quot;:513,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0}"><img title="Site Search - Results Returned" src="&quot;https:/github.com/searchdiscovery/client-fti-ga4-dl-spec/blob/main/images/Site%20Search%20%E2%80%93%20Results%20Returned.png&quot;" alt="" /></span></p>
