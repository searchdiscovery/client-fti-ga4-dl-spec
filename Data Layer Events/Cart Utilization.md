# Cart Utilization

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ event_data: null });  // Clear the previous event_data object.
dataLayer.push({
  "event": "cart_engagement",
  "detailed_event": "Cart Utilization",
    "action": "<action>",
    "event_data": {
        "cart_action": "<cart_action>",
        "file_lit_code": "<file_lit_code>",
        "file_name": "<file_name>"
    },
    "file_lit_code": "<file_lit_code>",
    "file_name": "<file_name>"
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|action|string|The generic action of an event property||||||||
|event_data.cart_action|string|The action the user took.|"Add to Cart", "Download from Cart", "Email from Cart", "Direct Mail"|||||||
|event_data.file_lit_code|string|This is the file lit code||||||||
|event_data.file_name|string|Captures the file name associated with file downloads.|Year End 2012.pdf, Operating Instructions.doc`|||||||
|file_lit_code|string|The literature code for the file.  Only applicable for US site||||||||
|file_name|string|The human readable file name - non-US sites will use the PDF file name|Fun Fact Sheet|||||||

## Attached Notes

<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Fire the code snippet below when a product is added to the cart or when the download/email/direct mail form is submitted successfully&quot;}" data-sheets-userformat="{&quot;2&quot;:14849,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0,&quot;14&quot;:{&quot;1&quot;:2,&quot;2&quot;:0},&quot;15&quot;:&quot;Arial&quot;,&quot;16&quot;:11}">Fire the code snippet below when a product is added to the cart or when the download/email/direct mail form is submitted successfully</span></p>
<p><span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Fire the code snippet below when a product is added to the cart or when the download/email/direct mail form is submitted successfully&quot;}" data-sheets-userformat="{&quot;2&quot;:14849,&quot;3&quot;:{&quot;1&quot;:0},&quot;12&quot;:0,&quot;14&quot;:{&quot;1&quot;:2,&quot;2&quot;:0},&quot;15&quot;:&quot;Arial&quot;,&quot;16&quot;:11}"><img title="Cart Utilization" src="https://github.com/searchdiscovery/client-fti-ga4-dl-spec/blob/main/images/Cart%20Utilization.png" alt="" /></span></p>
