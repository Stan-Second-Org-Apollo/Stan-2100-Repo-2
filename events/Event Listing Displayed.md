# Event Listing Displayed

### This event is part of the page load sequence, including virtual page loads in the case of single page apps, and must be pushed between the `Page Load Started` and `Page Load Completed` events.

## Javascript Code
```js
window.appEventData776 = window.appEventData776 || [];
appEventData776.push({
  "event": "Event Listing Displayed",
    "listingDisplayed": {
        "listingContext": "<listingContext>",
        "sortDefault": "<sortDefault>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|listingContext|string|Describes the context of a listing display \(sort changed, filter added, filter removed\)|Filter Added, Filter Removed, Sort Change, Pagination|||||||
|sortDefault|integer|The default sort value on listings|A to Z, Low to High, Newest to Oldest||||0|||
