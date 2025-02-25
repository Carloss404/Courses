## Control How Data Is Used in Google Analytics

**IP addresses:**
Google Analytics doesn't log or store individual IP addresses, so there's no need to change any settings.

**Data retention period:**
Set the amount of time before user-level and event-level data stored by Google Analytics is automatically detected from Analytics servers.

Note: The setting does not affect reports that rely on aggregated data.

**Consent Mode:**
Once implemented, Google's tags will dynamically adapt based on the consent status of your users, only using measurement tools for the specified purposes when consent has been given by the user.

**Disable collection of Google Signals Data:**
You can enable or disable collection of Google Signals Data on a per-region basis. If you edit Google-signals settings and disable collection for a region, Analytics maintains any historical data you've collected, but no additional data is collected after the time of the change.

**Granular location and device data:**
You can enable or disable the collection of granular location and device data on a per-region basis.

**Ads personalization:**
Ads personalization can be controlled in Property Settings to enable or disable it for users from any supported countries and/or U.S. states.

**Consent Mode:**
Consent mode lets you communicate your users' cookies or app identifier consent status to Google. Tags adjust their behavior and respect users' choices.

**IAB Europe Transparency & Consent Framework (TCF):**
The IAB Europe Transparency & Consent Framework (TCF) is an alternative way of obtaining and tracking consent state.

**Request data deletion:**
If you need to delete data from Google Analytics servers, you can submit a request for its removal. There's a seven-day grace period starting from the time you make the request before Analytics will begin the deletion process. All administrators and users with edit permission for your account will be informed of your request and have the ability to cancel the request during grace period.

**Delete user data:**
You can also delete a single user's data from your Analytics account. If you have edit permission for the account, use the user exploration technique found in the Explore section. Data associated with this user will be removed from the report within 72 hours and deleted from the Analytics servers in the next deletion process.

**Delete a property:**
If you have edit permission, you can delete a property from your Analytics account. Your property and all the reports and data in the property will be permanently deleted 35 days after being moved to the trash can. Once deleted, you can't retrieve any historical data or reinstate reports.

**Analytics User Deletion API:**
You can also use the Analytics User Deletion API to delete data for multiple users at one time.

### Module Questions

**Which data collection feature allows you to control the amount of time user-level and event-level data is stored by Google Analytics?**
Data retention period

---

## Choose how you share Analytics data with Google

Two types of modeling are available in Google Analytics to help you fill the gap in the data, while respecting user privacy.

**Behavioral modeling:**
Behavioral modeling models the behavior of users who decline analytics cookie consent based on the behavior of similar users who accept analytics cookies.

**Key events modeling:**
Google uses modeling to estimate key events that cannot be directly observed, for reasons such as user privacy or technical limitations. It can then attribute key events to their most likely source based on trends learned from observed data.

### Module Questions

**All of the following are examples of ways you can control your data within and using Google Analytics except:**
Robust acquisition and engagement reporting

---

## Connect Google Analytics with Other Tools

**Better cross-device and cross-platform tracking:**
By connecting with Analytics you can understand how users move between devices and platforms and how your advertising efforts influence their behavior. It can also help you to de-duplicate users.

**Create custom audiences for targeting:**
With Google Analytics, you can create custom audiences based on user behavior, which can be exported for targeting in DV360, SA360, and Google Ads. You can segment customers based on user behavior, supporting you in creating tailored and specific remarketing campaigns for customers who have engaged with your site before.

**Conversion tracking:**
By linking Google Analytics to your advertising platforms, you can track conversions more accurately and attribute them correctly, helping you make data-driven decisions on what channel or approach to invest in.

### Display & Video 360

**Benefits in Display & Video 360:**
- Conversions from Google Analytics for reporting and custom bidding, increasing ROI
- Audiences for reporting and remarketing

**Benefits in Analytics:**
- Display & Video 360 advertising in Analytics cross-channel reports, explorations, attribution, and advertising workspace.
- Display & Video 360 campaign and cost data is imported to Analytics

### Search Ads 360

**Benefits in Search Ads 360:**
- Conversions from Google Analytics for reporting and bidding
- Google Analytics engagement metrics will be available for reporting in Search Ads 360
- Direct audience export from Google Analytics to Search Ads 360 (New Search Ads 360 only)

**Benefits in Analytics:**
- Search Ads 360 campaign traffic surfaced in Analytics cross-channel reports, explorations, and advertising workspace
- Search Ads 360-specific reporting in the acquisition overview report
- Search Ads 360 metrics and dimensions like campaign, ad Group, and keyword available in reports

### Campaign Manager 360

**Benefits in Campaign Manager 360:**
- Conversions from Google Analytics for reporting and bidding
- Google Analytics attribution models available in Campaign Manager 360
- Floodlight integration also unlocks net-new bidding functionality which supports auto-bidding towards Analytics conversions in DV360 and SA360

**Benefits in Analytics:**
- Campaign Manager 360 campaign traffic surfaced in Analytics cross-channel reports, explorations, and advertising workspace
- Campaign Manager 360-specific reporting in the acquisition overview report
- CM360 metrics and dimensions in reporting

### Module Questions

**Roberto is eager to link Google Analytics to the other tools his business uses. He wants to get the data connected before a big holiday sale coming up. He's an Admin in Google Analytics and is very confident with the platform. But what other permissions does he need in SA360 before setting up the link?**
Admin

---

## Firebase Integration

### Firebase with Google Analytics

**Benefits in Firebase:**
Google Analytics for Firebase reports in the Firebase console. These reports include crash data, notification effectiveness, deep-link performance, in-app purchase data, and more.

**Benefits in Analytics:**
The Firebase integration is a key feature of Google Analytics as it enables app data to flow into Analytics. This integration powers any Analytics report that includes app data and allows for app data and website data to be analyzed together.

## Search Console Integration

### Search Console with Google Analytics

**Benefits in Search Console:**
Search Console data combined with Google Analytics data. Select the next card to see specific reports.

**Benefits in Analytics:**
- **Google Organic Search Queries report:** Display search queries and associated Search Console metrics for the linked Search Console property.
- **Google Organic Search Traffic report:** Displays landing pages with associated Search Console and Analytics metrics. You can drill into the data by the country and device dimensions.

### Module Questions

**Which integration enables the Google Organic Search Traffic report in Analytics?**
Search Console integration

---

## Combine Business Data in Google Analytics

**Data Import:**
Upload data from external sources and join it with your Analytics data.

**Measurement Protocol:**
Enhances measurement for web and app streams by sending events directly to Google Analytics servers in HTTP requests.

### Measurement Protocol

Measurement Protocol is a different method of sending data than gtag, Google Tag Manager, and the Firebase SDKs. It lets you send data to directly Analytics from internet-connected devices like a kiosk or point-of-sale system that complement your website or app.

In addition to sending new events, Measurement Protocol also lets you add information to events you've previously collected via gtag, Google Tag Manager, and the Firebase SDKs.

**Developers can use the Measurement Protocol to:**
- Tie online to offline behavior
- Measure interactions both client-side and server-side
- Send events that happen outside the web and app (e.g. offline conversions, order refund, in-store purchases)
- Incorporate events that cannot be tracked via gtag or the SDK

### Module Questions

**Which of these enhances measurement for web and app streams by sending events directly to Google Analytics servers in HTTP requests?**
- [ ] Admin API
- [x] Measurement Protocol
- [ ] HTTP request
- [ ] Data API

**When using Data Import, what *two* types of data are joined with Analytics data at reporting/query time**
- [ ] Offline event data
- [ ] User data
- [x] Item data
- [x] Cost data

---

## Export Google Analytics Data to BigQuery

**What is BigQuery?**
BigQuery is Google Cloud Platform's fully managed, petabyte-scale, and cost-effective analytics data warehouse. BigQuery lets you run analytics over vast amounts of data in near real time to help you turn big data into valuable business insights.

**How often is data exported to BigQuery?**
**Daily:** A once daily completed export or raw, unsampled Analytics event data from the previous day. Note: For standard customers, there is a one million events per day export limit.

**Streaming:** A real-time export of current-day Analytics event data with no export limit. Note, some data isn't included right away, like user-attribution data that may require more than 24 hours to fully process.

**User data export:** A daily export of all user data that has changed over the past day, enabling the export of an audience data, predictive data, and more.

**Fresh daily export:** The fresh daily export will support a service level agreement (SLA) that will guarantee a complete set of data by the same time each day. The exported data will be similar to the daily export.

Only available with Google Analytics 360.

### Module Questions

**True or False? You can choose the geographic location where your data is stored when it's exported from Google Analytics to BigQuery.**
True

**Which of the following is *not* something you can do with BigQuery export?**
- [ ] Export your data from BigQuery to external storage
- [ ] Import other data into BigQuery to combine with Analytics data
- [x] Send events from BigQuery directly to Google Analytics servers
- [ ] Export Analytics data to BigQuery and run SQL queries

---

## Get Enterprise Features with Analytics 360

**What is Analytics 360?**
Analytics 360 is the paid enterprise version of Google Analytics. Let's look at some features that come with Analytics 360 and the key differences between standard properties and 360 properties in Google Analytics.

### Additional setup options for your business

**Subproperties:** A subproperty gets its data from one other property called the source property. The data in a subproperty is typically a subset of the data in its source property.

**Roll-up properties:** A roll-up property contains data from two or more source properties. It can include source data from ordinary properties, but not other roll-up properties.

#### When to use subproperties

**Data governance:** One of the biggest use cases for subproperties is data governance -- controlling what data is included or excluded from a property. Subproperties let you filter data in or out to create the data set needed for a specific audience or use case. This allows for better organization of data, making it more easily accessible to certain audiences.

**User governance:** Another use case for subproperties is for user governance needs. Here's an example: You have strict company policies stating that one region (North America) can see a certain subset of data related to their region, but another region (South America) shouldn't have any access to the data.

#### When to use roll-up properties

**Combine products, brands, or regions:** Roll-up properties provide a broad view of your business across products, brands, or regions by combining data from multiple source properties into a single roll-up property. For example, if you have separate properties for multiple brands that your company owns, you can roll those up into a single property that provides an aggregate look at how those brands perform.

### Account structure using subproperties

Anders manages a large insurance company that offers the following policy types:
- Home insurance
- Car insurance
- Life insurance

![[Pasted image 20250210105159.png]]

### Account structure part 1 (using roll-up properties)

Hiroko owns and manages a retail company. The company has distinct brands for their product lines, including:
- Automotive goods
- Household goods
- Consumer electronics

![[Pasted image 20250210105359.png]]

### Account structure part 2

The parent company also has a loyalty rewards program that extends across all their individual brands. Hiroko's rewards team works at the parent company level and must see data for loyalty program participants across all brands together in the same property.

![[Pasted image 20250210105624.png]]

### Module Questions

**Which is a subproperty and which is a roll-up property?**

**A property that gets its data from one other source property.**
Subproperty

**A property that contains data from two or more source properties.**
Roll-up property

**Which of the following is not a feature unique to Analytics 360 properties?**
- [x] BigQuery export
- [ ] Roll-up properties
- [ ] Higher limits for conversions and audiences
- [ ] Subproperties

