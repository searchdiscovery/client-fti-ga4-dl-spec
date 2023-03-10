# Site Search View More

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "search_view_more",
  "detailed_event": "Site Search View More",
    "event_data": {
        "search_category": "<search_category>",
        "search_column": "<search_column>",
        "search_term": "<search_term>"
    },
    "search_category": "<search_category>",
    "search_column": "<search_column>",
    "search_term": "<search_term>"
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.search_category|string|A predefined list of search categories for FTI's search event|"instant-manager", "instant-fund", "instant-content", "all", "funds", "literature", "pages"|||||||
|event_data.search_column|string|The column of user interaction||||||||
|event_data.search_term|string|The keyword entered by a user for a search.||||||||
|search_category|string|A predefined list of search categories for the FTI "search" event|"instant-manager", "instant-fund", "instant-content", "all", "funds", "literature", "pages"|||||||
|search_column|string|The column of user interaction||||||||
|search_term|string|The keyword entered by a user for a search.||||||||

## Attached Notes

<p><span style="font-weight: 400;">Fire the code snippet below when the user clicks on a "view more" button</span></p>
<p><img title="Site Search View More" src="https://github.com/searchdiscovery/client-fti-ga4-dl-spec/blob/main/images/Site%20Search%20View%20More.png?raw=true" alt="" /></p>
