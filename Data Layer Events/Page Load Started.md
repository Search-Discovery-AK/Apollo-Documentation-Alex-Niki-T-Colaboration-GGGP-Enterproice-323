# Page Load Started

### Page Load Started is part of the page load sequence, including virtual page loads in the case of single page apps, and must be the first event pushed in the page load event sequence.

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Page Load Started",
    "page": {
        "dayOfWeek": "<dayOfWeek>",
        "isIncognitoMode": <isIncognitoMode>,
        "siteName": "<siteName>",
        "weekdayOrWeekend": "<weekdayOrWeekend>"
    },
    "page_data": {
        "hour": "<hour>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|page.dayOfWeek|string|The day of the week the activity occured.||||||||
|page.isIncognitoMode|integer|Set on all pages when user is in "incognito mode" in their browser.||||||||
|page.siteName|string|Common language used within the business to refer to the website. May be specific County Sites.|Prospecting-EU, Prospecting-US, Member Portal, Shop-CA, Shop-US, Shop-EU|||||||
|page.weekdayOrWeekend|string|Whether it was a week day or weekend when activity is occurred.||||||||
|page_data.hour|string|The time of activity at the top of the hour.||||||||




