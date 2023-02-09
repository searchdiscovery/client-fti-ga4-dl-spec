# Download Link Clicked

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "file_download",
  "detailed_event": "Download Link Clicked",
    "event_data": {
        "file_extension": "<file_extension>",
        "file_lit_code": "<file_lit_code>",
        "file_name": "<file_name>",
        "link_url": "<link_url>",
        "location": "<location>"
    },
    "file_extension": "<file_extension>",
    "file_lit_code": "<file_lit_code>",
    "file_name": "<file_name>",
    "link_url": "<link_url>",
    "location": "<location>"
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|event_data.file_extension|string|Captures the type of file that was downloaded \(i.e. PDF, EPUB, DMG\).|pdf, doc, csv, dmp, zip|||||||
|event_data.file_lit_code|string|This is the file lit code||||||||
|event_data.file_name|string|Captures the file name associated with file downloads.|Year End 2012.pdf, Operating Instructions.doc`|||||||
|event_data.link_url|string|The full URL of the link.||||||||
|event_data.location|string|The location on a page where a downloadable file is found||||||||
|file_extension|string|The file extension type|pdf,txt,doc,xls|||||||
|file_lit_code|string|The literature code for a downloaded file - applicable on to the US property|564-FF|||||||
|file_name|string|The human readable file name - non-US sites will use the PDF file name|Fun Fact Sheet|||||||
|link_url|string|This will inform the full URL to a downloaded file, if available||||||||
|location|string|This informs where a file download occurs, and is intended to help differentiate between Instant Search downloads or other areas where a download takes place|search|||||||




