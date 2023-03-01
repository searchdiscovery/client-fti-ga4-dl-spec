# Page Load Started

### 

## Javascript Code
```js
window.dataLayer = window.dataLayer || [];
dataLayer.push({ page_data: null });  // Clear the previous page_data object.
dataLayer.push({
  "event": "page_load_started",
  "detailed_event": "Page Load Started",
    "article_title": "<article_title>",
    "asset_class": "<asset_class>",
    "author": "<author>",
    "fund_brand": "<fund_brand>",
    "fund_category": "<fund_category>",
    "fund_class": "<fund_class>",
    "fund_name": "<fund_name>",
    "fund_number": "<fund_number>",
    "fund_tab": "<fund_tab>",
    "fund_ticker": "<fund_ticker>",
    "fund_type": "<fund_type>",
    "investment_theme": "<investment_theme>",
    "language_code": "<language_code>",
    "page_category": "<page_category>",
    "page_data": {
        "article_title": "<article_title>",
        "asset_class": "<asset_class>",
        "author": "<author>",
        "country": "<country>",
        "fund_brand": "<fund_brand>",
        "fund_category": "<fund_category>",
        "fund_class": "<fund_class>",
        "fund_name": "<fund_name>",
        "fund_number": "<fund_number>",
        "fund_tab": "<fund_tab>",
        "fund_ticker": "<fund_ticker>",
        "fund_type": "<fund_type>",
        "investment_theme": "<investment_theme>",
        "language": "<language>",
        "language_code": "<language_code>",
        "name": "<name>",
        "page_category": "<page_category>",
        "page_location": "<page_location>",
        "page_subcategory": "<page_subcategory>",
        "page_title": "<page_title>",
        "personalization_experience": "<personalization_experience>",
        "personalization_target": "<personalization_target>",
        "personalization_type": "<personalization_type>",
        "publication_series": "<publication_series>",
        "publish_date": "<publish_date>",
        "segmentation": "<segmentation>",
        "type": "<type>",
        "vehicle": "<vehicle>"
    },
    "page_location": "<page_location>",
    "page_subcategory": "<page_subcategory>",
    "page_title": "<page_title>",
    "page_type": "<page_type>",
    "personalization_experience": "<personalization_experience>",
    "personalization_target": "<personalization_target>",
    "personalization_type": "<personalization_type>",
    "publication_series": "<publication_series>",
    "publish_date": "<publish_date>",
    "segmentation": "<segmentation>",
    "vehicle": "<vehicle>"
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|article_title|string|The article title||||||||
|asset_class|string|The asset class tag of a page||||||||
|author|string|comma-separated list of author\(s\) for the article||||||||
|fund_brand|string|The brand associated with the fund|"Franklin Templeton", "Legg Mason", "LibertyShares"|||||||
|fund_category|string|The fund category|"Tax Free Income"|||||||
|fund_class|string|The class of the fund||||||||
|fund_name|string|The fund full name||||||||
|fund_number|string|The number of the fund||||||||
|fund_tab|string|The tab the user is on||||||||
|fund_ticker|string|The fund ticker symbol||||||||
|fund_type|string|The type of fund|"998"|||||||
|investment_theme|string|The theme tag of an article||||||||
|language_code|string|The four letter language code|"en-US", "en-CA", "fr-CA"|||||||
|page_category|string|The page category as defined by menu navigation|"investments & solutions"|||||||
|page_data.article_title|string|The article title||||||||
|page_data.asset_class|string|The asset class tag of the page||||||||
|page_data.author|string|The author of the article||||||||
|page_data.country|string|The country associated with the current page.|US, CA, FR, UK|||||||
|page_data.fund_brand|string|The brand associated with the fund|"Franklin Templeton", "Legg Mason", "Liberty Share"|||||||
|page_data.fund_category|string|The fund category||||||||
|page_data.fund_class|string|The class of the fund||||||||
|page_data.fund_name|string|The name of the fund||||||||
|page_data.fund_number|string|The number of the fund||||||||
|page_data.fund_tab|string|The tab the user is on||||||||
|page_data.fund_ticker|string|The fund ticker symbol||||||||
|page_data.fund_type|string|The type of fund||||||||
|page_data.investment_theme|string|The theme tag of an article||||||||
|page_data.language|string|The language of the current page, usually pulled from the &lt;html&gt; tag lang attribute.|en-us, en-gb, ch-cn, fr-ca, fr-fr|||||||
|page_data.language_code|string|The four letter language code|"en-US", "en-CA", "fr-CA"|||||||
|page_data.name|string|Captures the name of the page the user is on|product - XYZ123, Mens - Tops - Sweaters, Order Confirmation|||||||
|page_data.page_category|string|The page category as defined by menu navigation||||||||
|page_data.page_location|string|The url of the page currently being viewed.||||||||
|page_data.page_subcategory|string|The page subcategory as defined by menu navigation||||||||
|page_data.page_title|string|The title of the page currently being viewed, generally available in &lt;title&gt;.||||||||
|page_data.personalization_experience|string|A Yes or No, to identify whether the user was the target of a personalized experience||||||||
|page_data.personalization_target|string|The targeting that triggered the personalization||||||||
|page_data.personalization_type|string|The type of personalization||||||||
|page_data.publication_series|string|The series for the article||||||||
|page_data.publish_date|string|The article publish date||||||||
|page_data.segmentation|string|The segment attached to an article||||||||
|page_data.type|string|The type of page currently viewed.|home, pdp, article|||||||
|page_data.vehicle|string|This is the investment vehicle tag||||||||
|page_location|string|The full page url||||||||
|page_subcategory|string|The page subcategory as defined by menu navigation|"investment options"|||||||
|page_title|string|This is the page title for the UA reporting structure||||||||
|page_type|string|The page type||||||||
|personalization_experience|string|either yes or no to identify if a user has had a personalized experience or not.|"yes", "no"|||||||
|personalization_target|string|The targeting that triggered the personalization|"Edward Jones", "DC"|||||||
|personalization_type|string|The type of personalization|"firm", "web experience", "DC", "RIA"|||||||
|publication_series|string|the series for the article||||||||
|publish_date|string|The date article was published||||||||
|segmentation|string|The segment for an article||||||||
|vehicle|string|This is the investment vehicle tag|"mutual fund", "SMA", "ETF"|||||||




