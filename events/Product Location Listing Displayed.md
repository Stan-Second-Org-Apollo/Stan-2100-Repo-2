# Product Location Listing Displayed

### This event is part of the page load sequence, including virtual page loads in the case of single page apps, and must be pushed between the `Page Load Started` and `Page Load Completed` events.

## Javascript Code
```js
window.appEventData776 = window.appEventData776 || [];
appEventData776.push({
  "event": "Product Location Listing Displayed",
    "listingDisplayed": {
        "filterListLength": "<filterListLength>",
        "listingType": "<listingType>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|filterListLength|integer|The number of filterValue pairs in the filterList|0, 20, 12||||0|||
|listingType|string|The type of results being listed|text, product, location, event, room, product location|||||||
