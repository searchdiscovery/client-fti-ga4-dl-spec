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

## Attached Notes

<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Add the code snippet below to the click event of all download links.\n\nNotes:\nFile paths should denote that the item is a \&quot;download\&quot; and the path should also note the file extension of the document such as \&quot;.pdf\&quot;\nThe file path should also denote the lit code (the reference code for the literature) of the document. \nNote the lit code isn't applicable for documents such as transaction confirmations. \nThe title of the document should be human readable and understandable\nThe path of the file for transactions should not include user names or emails, as we cannot collect personally identifiable information&quot;}" data-sheets-userformat="{&quot;2&quot;:513,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0}">Add the code snippet below to the click event of all download links.<br /><br />Notes:<br />File paths should denote that the item is a "download" and the path should also note the file extension of the document such as ".pdf"<br />The file path should also denote the lit code (the reference code for the literature) of the document. <br />Note the lit code isn't applicable for documents such as transaction confirmations. <br />The title of the document should be human readable and understandable<br />The path of the file for transactions should not include user names or emails, as we cannot collect personally identifiable information</span></p>
<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Add the code snippet below to the click event of all download links.\n\nNotes:\nFile paths should denote that the item is a \&quot;download\&quot; and the path should also note the file extension of the document such as \&quot;.pdf\&quot;\nThe file path should also denote the lit code (the reference code for the literature) of the document. \nNote the lit code isn't applicable for documents such as transaction confirmations. \nThe title of the document should be human readable and understandable\nThe path of the file for transactions should not include user names or emails, as we cannot collect personally identifiable information&quot;}" data-sheets-userformat="{&quot;2&quot;:513,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0}"><img title="File Downloads" src="&quot;https:/github.com/searchdiscovery/client-fti-ga4-dl-spec/blob/main/images/File%20Downloads.png&quot;" alt="" /></span></p>
