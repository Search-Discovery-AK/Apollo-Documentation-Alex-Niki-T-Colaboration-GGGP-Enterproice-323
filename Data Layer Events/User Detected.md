# User Detected

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "User Detected",
    "user": {
        "affiliateCustomerID": "<affiliateCustomerID>",
        "country": "<country>",
        "custKey": "<custKey>",
        "loginStatus": "<loginStatus>",
        "loyalty": {
            "memberId": "<memberId>",
            "memberStatus": "<memberStatus>"
        },
        "loyaltyPoints": <loyaltyPoints>,
        "profileAttributesList": "<profileAttributesList>",
        "userType": "<userType>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|user.affiliateCustomerID|string|The user ID of user who arrived at the website via a third party partner.||||||||
|user.country|string|The country associated with this user's profile.|USA, Canada|||||||
|user.custKey|string|Unique identifier of a customer.  Any id's considered PII must be hashed. ||||||||
|user.loginStatus|string|Describes the login state of the user|logged in, logged out, guest|||||||
|user.loyalty.memberId|string|Member Identifier in a Loyalty program|abc1234, def876, 87987659|||||||
|user.loyalty.memberStatus|string|Member status, level, or tier in a Loyalty program|Gold, Bronze, Platinum, Diamond, Silver|||||||
|user.loyaltyPoints|integer|Number of loyalty points |100, 101, 1000||||0|||
|user.profileAttributesList|string|A twice delimited string of key \/ value pairs.  Use \~ between key and value.  Use \| between pairs|homeStore\~234\|loyaltyTier\~gold\|memberSince\~2002|||||||
|user.userType|string|Describes the type of the user.  Often used to differentiate customers from employees or associates. |employee, guest, agent, customer|||||||




