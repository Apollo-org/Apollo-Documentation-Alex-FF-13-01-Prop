# User Detected

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];;;
appEventData.push({
  "event": "User Detected",
    "user": {
        "affiliateCustomerID": "<affiliateCustomerID>",
        "custKey": "<custKey>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|affiliateCustomerID|string|The user ID of user who arrived at the website via a third party partner.||||||||
|custKey|string|Unique identifier of a customer.  Any id's considered PII must be hashed. ||||||||




