# User Detected

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({
  "event": "detect_user",
  "detailed_event": "User Detected",
    "accounts_assigned": "<accounts_assigned>",
    "country_code": "<country_code>",
    "data_service_actor": "<data_service_actor>",
    "dealer_number": "<dealer_number>",
    "express_number": "<express_number>",
    "firm_channel": "<firm_channel>",
    "firm_name": "<firm_name>",
    "global_id": "<global_id>",
    "is_internal_user": "<is_internal_user>",
    "logged_in_status": "<logged_in_status>",
    "market_code": "<market_code>",
    "ost_id": "<ost_id>",
    "riva_id": "<riva_id>",
    "role_selected": "<role_selected>",
    "role_type_track": "<role_type_track>",
    "state_code": "<state_code>",
    "subsegment": "<subsegment>",
    "user_data": {
        "country_code": "<country_code>",
        "data_service_actor": "<data_service_actor>",
        "dealer_number": "<dealer_number>",
        "express_number": "<express_number>",
        "firm_channel": "<firm_channel>",
        "firm_name": "<firm_name>",
        "global_id": "<global_id>",
        "is_internal_user": "<is_internal_user>",
        "logged_in_status": "<logged_in_status>",
        "market_code": "<market_code>",
        "ost_id": "<ost_id>",
        "riva_id": "<riva_id>",
        "role_selected": "<role_selected>",
        "role_type_track": "<role_type_track>",
        "state_code": "<state_code>",
        "subsegment": "<subsegment>",
        "user_group": "<user_group>",
        "user_sys_no": "<user_sys_no>",
        "web_experience": "<web_experience>",
        "zip": "<zip>"
    },
    "user_group": "<user_group>",
    "user_sys_no": "<user_sys_no>",
    "web_experience": "<web_experience>",
    "zip": "<zip>"
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|accounts_assigned|string|The accounts assigned||||||||
|country_code|string|The two character country code||||||||
|data_service_actor|string|The data service actor||||||||
|dealer_number|string|The dealer number||||||||
|express_number|string|The express number||||||||
|firm_channel|string|The firm channel||||||||
|firm_name|string|The firm name||||||||
|global_id|string|The global ID||||||||
|is_internal_user|string|identifies if the visitor is an FT employee or not so we can exclude them from reporting||||||||
|logged_in_status|string|either "logged in" or "logged out"|"logged in", "logged out"|||||||
|market_code|string|Market code the website serves||||||||
|ost_id|string|The OST ID||||||||
|riva_id|string|The RIVA ID||||||||
|role_selected|string|the role the user has self-selected on the site||||||||
|role_type_track|string|uses the role type hierarchy||||||||
|state_code|string|The two digit state code||||||||
|subsegment|string|The subsegment||||||||
|user_data.country_code|string|The two character country code||||||||
|user_data.data_service_actor|string|The data service actor||||||||
|user_data.dealer_number|string|The dealer number||||||||
|user_data.express_number|string|The express number||||||||
|user_data.firm_channel|string|The firm channel||||||||
|user_data.firm_name|string|The firm namne||||||||
|user_data.global_id|string|The global ID||||||||
|user_data.is_internal_user|string|identifier is the visitor is an FT employee or not so we can exclude them from reporting||||||||
|user_data.logged_in_status|string|Either "logged in" or "logged out"|"logged in", "logged out"|||||||
|user_data.market_code|string|Market code the website serves||||||||
|user_data.ost_id|string|The OST ID||||||||
|user_data.riva_id|string|The RIVA ID||||||||
|user_data.role_selected|string|The role the user has self-selected on the site||||||||
|user_data.role_type_track|string|uses the role type hierarchy||||||||
|user_data.state_code|string|The two character state code||||||||
|user_data.subsegment|string|The subsegment||||||||
|user_data.user_group|string|The user group||||||||
|user_data.user_sys_no|string|The user system number||||||||
|user_data.web_experience|string|The web experience||||||||
|user_data.zip|string|The zip code||||||||
|user_group|string|The user group||||||||
|user_sys_no|string|The user system number||||||||
|web_experience|string|The web experience||||||||
|zip|string|The zip code||||||||




