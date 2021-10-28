# Page Load Started

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Page Load Started",
    "page": {
        "breadcrumbs": "<breadcrumbs>",
        "dayOfWeek": "<dayOfWeek>",
        "detailedPageName": "<detailedPageName>",
        "flowStep": "<flowStep>",
        "hour": "<hour>",
        "internalBusinessOwner": "<internalBusinessOwner>",
        "isIncognitoMode": "<isIncognitoMode>",
        "pageCategory": "<pageCategory>",
        "pageExperience": "<pageExperience>",
        "pageName": "<pageName>",
        "pageTitle": "<pageTitle>",
        "pageType": "<pageType>",
        "platform": "<platform>",
        "releaseVersion": "<releaseVersion>",
        "siteCountry": "<siteCountry>",
        "siteCurrency": "<siteCurrency>",
        "siteExperience": "<siteExperience>",
        "siteLanguage": "<siteLanguage>",
        "siteName": "<siteName>",
        "siteType": "<siteType>",
        "subsection": "<subsection>",
        "subsection2": "<subsection2>",
        "subsection3": "<subsection3>",
        "weekdayOrWeekend": "<weekdayOrWeekend>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|breadcrumbs|string|A delimited list of hierarchical sections that describe the current page's location within the navigation of the site.|Home&gt;Women&gt;Tops&gt;Sweaters, Mens - Tops - Sweaters - Supmina, Wool, Rayon, Checkout &gt; Order Thank You|||||||
|dayOfWeek|string|The day of the week the activity occured.||||||||
|detailedPageName|string|Describes the page in more detail than the pageName attribute|product - XYZ123 - super cotton neck scarf, Mens - Tops - Sweaters - Supmina, Wool, Rayon, Order Confirmation - 098fghjkl|||||||
|flowStep|string|Describes the step withing a multi-step process or flow.|Booking 2.a, Booking 2.b, Booking 3, Booking 4|||||||
|hour|string|The time of activity at the top of the hour.||||||||
|internalBusinessOwner|string|Describes the internal team who manages this particular page of the website.|XX product management, marketing, vendor name|||||||
|isIncognitoMode|integer|Set on all pages when user is in "incognito mode" in their browser.||||||||
|pageCategory|string|General category or Site Section of the page. Top level of page hierarchy.|Home, About Us, Shop, Account, Blog, Investors|||||||
|pageExperience|string|When a feature ramp up is taking place, capture a code to identify users receiving that feature's experience.||||||||
|pageName|string|Describes the page and its content specifically. |product - XYZ123, Mens - Tops - Sweaters, Order Confirmation|||||||
|pageTitle|string|HTML title tag for the page||||||||
|pageType|string|Describes what purpose the page serves. Often aligns with the CMS template.|Home, Event Detail, Property Detail, Product Listing, Blog Post, Shopping Cart|||||||
|platform|string|The technology platform version of the site that the user is experiencing.||||||||
|releaseVersion|string|Set to the information about the technology release that is most current on the page.||||||||
|siteCountry|string|Indicates the primary country served by the site. ISO 3166 \(alpha-2\) Uppercase.|US, CA, FR, UK|^[A-Z]{2}$||||||
|siteCurrency|string|Currency in which prices are displayed.  ISO 4217 \(3 character alpha\), uppercase|USD, CAD, EUR, GBP, CHF|^[A-Z]{3}$||||||
|siteExperience|string|Describes the version of the site that is being shown|Responsive, Mobile, Desktop|||||||
|siteLanguage|string|Language in which the site is presented ISO 639-1 code. |en-us, en-gb, ch-cn, fr-ca, fr-fr, da|^[a-z]{2}([-]{1}[a-z]{2}){0,1}$||||||
|siteName|string|Common language used within the business to refer to the website. May be specific County Sites.|Prospecting-EU, Prospecting-US, Member Portal, Shop-CA, Shop-US, Shop-EU|||||||
|siteType|string|Common language description of the site type of purpose. May be used to group siteName.|Prospecting, Shop, Members, Brand|||||||
|subsection|string|First sub-level of hierarchy under pageCategory or Site Section. |Shop &gt; Kids, Shop &gt; Mens, Shop &gt; Womens|||||||
|subsection2|string|Second sub-level of hierarchy under pageCategory or Site Section. |Shop &gt; Kids &gt; Tops, Shop &gt; Mens &gt; Shoes|||||||
|subsection3|string|Third sub-level of hierarchy under pageCategory or Site Section. |Shop &gt; Kids &gt; Tops &gt; Tees, Shop &gt; Mens &gt; Shoes &gt; Oxfords|||||||
|weekdayOrWeekend|string|Whether it was a week day or weekend when activity is occurred.||||||||




