# Product Return Completed

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Product Return Completed",
    "eventDetails": {
        "productQuantity": <productQuantity>
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|eventDetails.productQuantity|number|Number of products associated with a product self return.||||||||




