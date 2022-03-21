# User Visit Started

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "User Visit Started",
    "user": {
        "hasPersistedCart": <hasPersistedCart>
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|user.hasPersistedCart|boolean|Indicator of the user has a persisted shopping cart|TRUE, FALSE|||||||




