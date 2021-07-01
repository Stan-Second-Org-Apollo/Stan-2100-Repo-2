# Product Removed from Wishlist

### 

## Javascript Code
```js
window.appEventData776 = window.appEventData776 || [];
appEventData776.push({
  "event": "Product Removed from Wishlist",
    "product": [
        {
            "productInfo": {
                "productID": "<productID>"
            }
        }
    ],
    "wishlist": {
        "wishlistID": "<wishlistID>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|productID|string|Unique Identifier of a product or offering.  Must match the format of back-end systems if used as a key for import of product meta data. Most often, one level above SKU for products with SKU variants. |155, 65588, 987764448|||||||
|wishlistID|string|Back-end identifier for a wishlist|12345, 435678, 34567, XCV456, XCV876|||||||
