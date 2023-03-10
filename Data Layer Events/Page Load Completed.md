# Page Load Completed

### Page Load Completed is part of the page load sequence, including virtual page loads in the case of single page apps, and must be the last event pushed in the page load event sequence.

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({
  "event": "page_view",
  "detailed_event": "Page Load Completed"
});
```





## Attached Notes

<table style="border-collapse: collapse; width: 55%; border-style: solid;" border="1">
<tbody>
<tr>
<td>&nbsp;</td>
<td>Current event</td>
<td>New event</td>
</tr>
<tr>
<td>Page Load Started</td>
<td>pageView</td>
<td>page_load_started</td>
</tr>
<tr>
<td>User Detected</td>
<td>datalayer_loaded</td>
<td>detect_user</td>
</tr>
<tr>
<td>Page Load Completed</td>
<td>&nbsp;</td>
<td>page_view</td>
</tr>
</tbody>
</table>
<p>&nbsp;<br />Page Load Started &gt; User Detected &gt; Page Load Completed</p>
