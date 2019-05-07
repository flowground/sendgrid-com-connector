# ![LOGO](logo.png) SendGrid v3 **flow**ground Connector

## Description

A generated **flow**ground connector for the SendGrid v3 API (version 3.0).

Generated from: https://api.apis.guru/v2/specs/sendgrid.com/3.0/swagger.json<br/>
Generated at: 2019-05-07T17:44:00+03:00

## API Description

# The SendGrid Web API V3 Documentation

This is the entirety of the documented v3 endpoints. We have updated all the descriptions, parameters, requests, and responses.

## Authentication 

Every endpoint requires Authentication in the form of an Authorization Header:

Authorization: Bearer API_KEY

## Authorization

Supported authorization schemes:
- API Key
## Actions

### Retrieve all recent access attempts

> **This endpoint allows you to retrieve a list of all of the IP addresses that recently attempted to access your account either through the User Interface or the API.**<br/>
> <br/>
> IP Access Management allows you to control which IP addresses can be used to access your account, either through the User Interface or the API. There is no limit to the number of IP addresses that you can add to your whitelist. It is possible to remove your own IP address from the whitelist, thus preventing yourself from accessing your account.<br/>
> <br/>
> For more information, please see our [User Guide](http://sendgrid.com/docs/User_Guide/Settings/ip_access_management.html).

*Tags:* `IP Access Management`

#### Input Parameters
* `limit` - _optional_ - Limits the number of IPs to return.
* `on-behalf-of` - _optional_

### Remove one or more IPs from the whitelist

> **This endpoint allows you to remove one or more IPs from your IP whitelist.**<br/>
> <br/>
> You can remove one IP at a time, or you can remove multiple IP addresses.<br/>
> <br/>
> IP Access Management allows you to control which IP addresses can be used to access your account, either through the User Interface or the API. There is no limit to the number of IP addresses that you can add to your whitelist. It is possible to remove your own IP address from the whitelist, thus preventing yourself from accessing your account.<br/>
> <br/>
> For more information, please see our [User Guide](http://sendgrid.com/docs/User_Guide/Settings/ip_access_management.html).

*Tags:* `IP Access Management`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve a list of currently whitelisted IPs

> **This endpoint allows you to retrieve a list of IP addresses that are currently whitelisted.**<br/>
> <br/>
> IP Access Management allows you to control which IP addresses can be used to access your account, either through the User Interface or the API. There is no limit to the number of IP addresses that you can add to your whitelist. It is possible to remove your own IP address from the whitelist, thus preventing yourself from accessing your account.<br/>
> <br/>
> For more information, please see our [User Guide](http://sendgrid.com/docs/User_Guide/Settings/ip_access_management.html).

*Tags:* `IP Access Management`

#### Input Parameters
* `on-behalf-of` - _optional_

### Add one or more IPs to the whitelist

> **This endpoint allows you to add one or more IP addresses to your IP whitelist.**<br/>
> <br/>
> When adding an IP to your whitelist, include the IP address in an array. You can whitelist one IP at a time, or you can whitelist multiple IPs at once.<br/>
> <br/>
> IP Access Management allows you to control which IP addresses can be used to access your account, either through the User Interface or the API. There is no limit to the number of IP addresses that you can add to your whitelist. It is possible to remove your own IP address from the whitelist, thus preventing yourself from accessing your account.<br/>
> <br/>
> For more information, please see our [User Guide](http://sendgrid.com/docs/User_Guide/Settings/ip_access_management.html).

*Tags:* `IP Access Management`

#### Input Parameters
* `on-behalf-of` - _optional_

### Remove a specific IP from the whitelist

> **This endpoint allows you to remove a specific IP address from your IP whitelist.**<br/>
> <br/>
> When removing a specific IP address from your whitelist, you must include the ID in your call.<br/>
> <br/>
> IP Access Management allows you to control which IP addresses can be used to access your account, either through the User Interface or the API. There is no limit to the number of IP addresses that you can add to your whitelist. It is possible to remove your own IP address from the whitelist, thus preventing yourself from accessing your account.<br/>
> <br/>
> For more information, please see our [User Guide](http://sendgrid.com/docs/User_Guide/Settings/ip_access_management.html).

*Tags:* `IP Access Management`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve a specific whitelisted IP

> **This endpoint allows you to retreive a specific IP address that has been whitelisted.**<br/>
> <br/>
> You must include the ID for the specific IP address you want to retrieve in your call.<br/>
> <br/>
> IP Access Management allows you to control which IP addresses can be used to access your account, either through the User Interface or the API. There is no limit to the number of IP addresses that you can add to your whitelist. It is possible to remove your own IP address from the whitelist, thus preventing yourself from accessing your account.<br/>
> <br/>
> For more information, please see our [User Guide](http://sendgrid.com/docs/User_Guide/Settings/ip_access_management.html).

*Tags:* `IP Access Management`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve all alerts

> **This endpoint allows you to retieve all of your alerts.**<br/>
> <br/>
> Alerts allow you to specify an email address to receive notifications regarding your email usage or statistics. <br/>
> * Usage alerts allow you to set the threshold at which an alert will be sent.<br/>
> * Stats notifications allow you to set how frequently you would like to receive email statistics reports. For example, "daily", "weekly", or "monthly".<br/>
> <br/>
> For more information about alerts, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/alerts.html).

*Tags:* `Alerts`

#### Input Parameters
* `Authorization` - _optional_
* `on-behalf-of` - _optional_

### Create a new Alert

> **This endpoint allows you to create a new alert.**<br/>
> <br/>
> Alerts allow you to specify an email address to receive notifications regarding your email usage or statistics. There are two types of alerts that can be created with this endpoint:<br/>
> <br/>
> * `usage_limit` allows you to set the threshold at which an alert will be sent.<br/>
> * `stats_notification` allows you to set how frequently you would like to receive email statistics reports. For example, "daily", "weekly", or "monthly".<br/>
> <br/>
> For more information about alerts, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/alerts.html).

*Tags:* `Alerts`

#### Input Parameters
* `Authorization` - _optional_
* `on-behalf-of` - _optional_

### Delete an alert

> **This endpoint allows you to delete an alert.**<br/>
> <br/>
> Alerts allow you to specify an email address to receive notifications regarding your email usage or statistics. <br/>
> * Usage alerts allow you to set the threshold at which an alert will be sent.<br/>
> * Stats notifications allow you to set how frequently you would like to receive email statistics reports. For example, "daily", "weekly", or "monthly".<br/>
> <br/>
> For more information about alerts, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/alerts.html).

*Tags:* `Alerts`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve a specific alert

> **This endpoint allows you to retrieve a specific alert.**<br/>
> <br/>
> Alerts allow you to specify an email address to receive notifications regarding your email usage or statistics. <br/>
> * Usage alerts allow you to set the threshold at which an alert will be sent.<br/>
> * Stats notifications allow you to set how frequently you would like to receive email statistics reports. For example, "daily", "weekly", or "monthly".<br/>
> <br/>
> For more information about alerts, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/alerts.html).

*Tags:* `Alerts`

#### Input Parameters
* `Authorization` - _optional_
* `on-behalf-of` - _optional_

### Update an alert

> **This endpoint allows you to update an alert.**<br/>
> <br/>
> Alerts allow you to specify an email address to receive notifications regarding your email usage or statistics. <br/>
> * Usage alerts allow you to set the threshold at which an alert will be sent.<br/>
> * Stats notifications allow you to set how frequently you would like to receive email statistics reports. For example, "daily", "weekly", or "monthly".<br/>
> <br/>
> For more information about alerts, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/alerts.html).

*Tags:* `Alerts`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve all API Keys belonging to the authenticated user

> **This endpoint allows you to retrieve all API Keys that belong to the authenticated user.**<br/>
> <br/>
> The API Keys feature allows customers to be able to generate an API Key credential which can be used for authentication with the SendGrid v3 Web API or the [Mail API Endpoint](https://sendgrid.com/docs/API_Reference/Web_API/mail.html).

*Tags:* `API Keys`

#### Input Parameters
* `limit` - _optional_
* `on-behalf-of` - _optional_

### Create API keys

> **This endpoint allows you to create a new random API Key for the user.**<br/>
> <br/>
> A JSON request body containing a "name" property is required. If number of maximum keys is reached, HTTP 403 will be returned.<br/>
> <br/>
> There is a limit of 100 API Keys on your account.<br/>
> <br/>
> The API Keys feature allows customers to be able to generate an API Key credential which can be used for authentication with the SendGrid v3 Web API or the [Mail API Endpoint](https://sendgrid.com/docs/API_Reference/Web_API/mail.html).<br/>
> <br/>
> See the [API Key Permissions List](https://sendgrid.com/docs/API_Reference/Web_API_v3/API_Keys/api_key_permissions_list.html) for a list of all available scopes.

*Tags:* `API Keys`

#### Input Parameters
* `on-behalf-of` - _optional_

### Delete API keys

> **This endpoint allows you to revoke an existing API Key**<br/>
> <br/>
> Authentications using this API Key will fail after this request is made, with some small propogation delay.If the API Key ID does not exist an HTTP 404 will be returned.<br/>
> <br/>
> The API Keys feature allows customers to be able to generate an API Key credential which can be used for authentication with the SendGrid v3 Web API or the [Mail API Endpoint](https://sendgrid.com/docs/API_Reference/Web_API/mail.html).<br/>
> <br/>
> ## URI Parameters<br/>
> <br/>
> | URI Parameter   | Type  | Required?  | Description  |<br/>
> |---|---|---|---|<br/>
> |api_key_id |string | required | The ID of the API Key you are deleting.|

*Tags:* `API Keys`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve an existing API Key

> **This endpoint allows you to retrieve a single api key.**<br/>
> <br/>
> If the API Key ID does not exist an HTTP 404 will be returned.

*Tags:* `API Keys`

#### Input Parameters
* `on-behalf-of` - _optional_

### Update API keys

> **This endpoint allows you to update the name of an existing API Key.**<br/>
> <br/>
> A JSON request body with a "name" property is required.<br/>
> <br/>
> The API Keys feature allows customers to be able to generate an API Key credential which can be used for authentication with the SendGrid v3 Web API or the [Mail API Endpoint](https://sendgrid.com/docs/API_Reference/Web_API/mail.html).<br/>
> <br/>
> ## URI Parameters<br/>
> <br/>
> | URI Parameter   | Type  | Required?  | Description  |<br/>
> |---|---|---|---|<br/>
> |api_key_id |string | required | The ID of the API Key you are updating.|

*Tags:* `API Keys`

#### Input Parameters
* `on-behalf-of` - _optional_

### Update the name & scopes of an API Key

> **This endpoint allows you to update the name and scopes of a given API key.**<br/>
> <br/>
> A JSON request body with a "name" property is required.<br/>
> Most provide the list of all the scopes an api key should have.<br/>
> <br/>
> The API Keys feature allows customers to be able to generate an API Key credential which can be used for authentication with the SendGrid v3 Web API or the [Mail API Endpoint](https://sendgrid.com/docs/API_Reference/Web_API/mail.html).

*Tags:* `API Keys`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve information about multiple suppression groups

> **This endpoint allows you to retrieve information about multiple suppression groups.**<br/>
> <br/>
> This endpoint will return information for each group ID that you include in your request. To add a group ID to your request, simply append `&id=` followed by the group ID.<br/>
> <br/>
> Suppressions are a list of email addresses that will not receive content sent under a given [group](https://sendgrid.com/docs/API_Reference/Web_API_v3/Suppression_Management/groups.html).<br/>
> <br/>
> Suppression groups, or [unsubscribe groups](https://sendgrid.com/docs/API_Reference/Web_API_v3/Suppression_Management/groups.html), allow you to label a category of content that you regularly send. This gives your recipients the ability to opt out of a specific set of your email. For example, you might define a group for your transactional email, and one for your marketing email so that your users can continue recieving your transactional email witout having to receive your marketing content.

*Tags:* `Suppressions - Unsubscribe Groups`

#### Input Parameters
* `id` - _optional_ - The ID of a suppression group that you want to retrieve information for.
* `on-behalf-of` - _optional_

### Create a new suppression group

> **This endpoint allows you to create a new suppression group.**<br/>
> <br/>
> Suppression groups, or unsubscribe groups, are specific types or categories of email that you would like your recipients to be able to unsubscribe from. For example: Daily Newsletters, Invoices, System Alerts.<br/>
> <br/>
> The **name** and **description** of the unsubscribe group will be visible by recipients when they are managing their subscriptions.<br/>
> <br/>
> Each user can create up to 25 different suppression groups.

*Tags:* `Suppressions - Unsubscribe Groups`

#### Input Parameters
* `on-behalf-of` - _optional_

### Delete a suppression group.

> **This endpoint allows you to delete a suppression group.**<br/>
> <br/>
> You can only delete groups that have not been attached to sent mail in the last 60 days. If a recipient uses the "one-click unsubscribe" option on an email associated with a deleted group, that recipient will be added to the global suppression list.<br/>
> <br/>
> Suppression groups, or unsubscribe groups, are specific types or categories of email that you would like your recipients to be able to unsubscribe from. For example: Daily Newsletters, Invoices, System Alerts.<br/>
> <br/>
> The **name** and **description** of the unsubscribe group will be visible by recipients when they are managing their subscriptions.<br/>
> <br/>
> Each user can create up to 25 different suppression groups.

*Tags:* `Suppressions - Unsubscribe Groups`

#### Input Parameters
* `on-behalf-of` - _optional_

### Get information on a single suppression group.

> **This endpoint allows you to retrieve a single suppression group.**<br/>
> <br/>
> Suppression groups, or unsubscribe groups, are specific types or categories of email that you would like your recipients to be able to unsubscribe from. For example: Daily Newsletters, Invoices, System Alerts.<br/>
> <br/>
> The **name** and **description** of the unsubscribe group will be visible by recipients when they are managing their subscriptions.<br/>
> <br/>
> Each user can create up to 25 different suppression groups.

*Tags:* `Suppressions - Unsubscribe Groups`

#### Input Parameters
* `on-behalf-of` - _optional_

### Update a suppression group.

> **This endpoint allows you to update or change a suppression group.**<br/>
> <br/>
> Suppression groups, or unsubscribe groups, are specific types or categories of email that you would like your recipients to be able to unsubscribe from. For example: Daily Newsletters, Invoices, System Alerts.<br/>
> <br/>
> The **name** and **description** of the unsubscribe group will be visible by recipients when they are managing their subscriptions.<br/>
> <br/>
> Each user can create up to 25 different suppression groups.

*Tags:* `Suppressions - Unsubscribe Groups`

#### Input Parameters
* `Authorization` - _required_
* `on-behalf-of` - _optional_

### Retrieve all suppressions for a suppression group

> **This endpoint allows you to retrieve all suppressed email addresses belonging to the given group.**<br/>
> <br/>
> Suppressions are recipient email addresses that are added to [unsubscribe groups](https://sendgrid.com/docs/API_Reference/Web_API_v3/Suppression_Management/groups.html). Once a recipient's address is on the suppressions list for an unsubscribe group, they will not receive any emails that are tagged with that unsubscribe group.

*Tags:* `Suppressions - Suppressions`

#### Input Parameters
* `on-behalf-of` - _optional_

### Add suppressions to a suppression group

> **This endpoint allows you to add email addresses to an unsubscribe group.**<br/>
> <br/>
> If you attempt to add suppressions to a group that has been deleted or does not exist, the suppressions will be added to the global suppressions list.<br/>
> <br/>
> Suppressions are recipient email addresses that are added to [unsubscribe groups](https://sendgrid.com/docs/API_Reference/Web_API_v3/Suppression_Management/groups.html). Once a recipient's address is on the suppressions list for an unsubscribe group, they will not receive any emails that are tagged with that unsubscribe group.

*Tags:* `Suppressions - Suppressions`

#### Input Parameters
* `on-behalf-of` - _optional_

### Search for suppressions within a group

> **This endpoint allows you to search a suppression group for multiple suppressions.**<br/>
> <br/>
> When given a list of email addresses and a group ID, this endpoint will return only the email addresses that have been unsubscribed from the given group.<br/>
> <br/>
> Suppressions are a list of email addresses that will not receive content sent under a given [group](https://sendgrid.com/docs/API_Reference/Web_API_v3/Suppression_Management/groups.html).

*Tags:* `Suppressions - Suppressions`

#### Input Parameters
* `on-behalf-of` - _optional_

### Delete a suppression from a suppression group

> **This endpoint allows you to remove a suppressed email address from the given suppression group.**<br/>
> <br/>
> Suppressions are recipient email addresses that are added to [unsubscribe groups](https://sendgrid.com/docs/API_Reference/Web_API_v3/Suppression_Management/groups.html). Once a recipient's address is on the suppressions list for an unsubscribe group, they will not receive any emails that are tagged with that unsubscribe group.

*Tags:* `Suppressions - Suppressions`

#### Input Parameters
* `on-behalf-of` - _optional_
* `email` - _required_ - The email address that you want to remove from the suppression group.

### Retrieve all suppressions

> **This endpoint allows you to retrieve a list of all suppressions.**<br/>
> <br/>
> Suppressions are a list of email addresses that will not receive content sent under a given [group](https://sendgrid.com/docs/API_Reference/Web_API_v3/Suppression_Management/groups.html).

*Tags:* `Suppressions - Suppressions`

#### Input Parameters
* `on-behalf-of` - _optional_

### Add recipient addresses to the global suppression group.

> **This endpoint allows you to add one or more email addresses to the global suppressions group.**<br/>
> <br/>
> A global suppression (or global unsubscribe) is an email address of a recipient who does not want to receive any of your messages. A globally suppressed recipient will be removed from any email you send. For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/global_unsubscribes.html).

*Tags:* `Suppressions - Global Suppressions`

#### Input Parameters
* `on-behalf-of` - _optional_

### Delete a Global Suppression

> **This endpoint allows you to remove an email address from the global suppressions group.**<br/>
> <br/>
> A global suppression (or global unsubscribe) is an email address of a recipient who does not want to receive any of your messages. A globally suppressed recipient will be removed from any email you send. For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/global_unsubscribes.html).

*Tags:* `Suppressions - Global Suppressions`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve a Global Suppression

> **This endpoint allows you to retrieve a global suppression. You can also use this endpoint to confirm if an email address is already globally suppresed.**<br/>
> <br/>
> If the email address you include in the URL path parameter `{email}` is alreayd globally suppressed, the response will include that email address. If the address you enter for `{email}` is not globally suppressed, an empty JSON object `{}` will be returned.<br/>
> <br/>
> A global suppression (or global unsubscribe) is an email address of a recipient who does not want to receive any of your messages. A globally suppressed recipient will be removed from any email you send. For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/global_unsubscribes.html).

*Tags:* `Suppressions - Global Suppressions`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve all suppression groups for an email address

> **This endpoint returns the list of all groups that the given email address has been unsubscribed from.**<br/>
> <br/>
> Suppressions are a list of email addresses that will not receive content sent under a given [group](https://sendgrid.com/docs/API_Reference/Web_API_v3/Suppression_Management/groups.html).

*Tags:* `Suppressions - Suppressions`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve email statistics by browser.

> **This endpoint allows you to retrieve your email statistics segmented by browser type.**<br/>
> <br/>
> **We only store up to 7 days of email activity in our database.** By default, 500 items will be returned per request via the Advanced Stats API endpoints.<br/>
> <br/>
> Advanced Stats provide a more in-depth view of your email statistics and the actions taken by your recipients. You can segment these statistics by geographic location, device type, client type, browser, and mailbox provider. For more information about statistics, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Statistics/index.html).

*Tags:* `Stats`

#### Input Parameters
* `start_date` - _required_ - The starting date of the statistics to retrieve. Must follow format YYYY-MM-DD.
* `end_date` - _optional_ - The end date of the statistics to retrieve. Defaults to today.
* `limit` - _optional_ - The number of results to include on each page.
* `offset` - _optional_ - The number of results to exclude.
* `aggregated_by` - _optional_ - How to group the stats. Must be either "day", "week", or "month".
    Possible values: day, week, month.
* `browsers` - _optional_ - The browsers to get statistics for. You can include up to 10 different browsers by including this parameter multiple times.
* `on-behalf-of` - _optional_

### Retrieve all Campaigns

> **This endpoint allows you to retrieve a list of all of your campaigns.**<br/>
> <br/>
> Returns campaigns in reverse order they were created (newest first).<br/>
> <br/>
> Returns an empty array if no campaigns exist.<br/>
> <br/>
> For more information:<br/>
> <br/>
> * [User Guide > Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html)

*Tags:* `Campaigns API`

#### Input Parameters
* `limit` - _optional_ - The number of results you would like to receive at a time.
* `offset` - _optional_ - The index of the first campaign to return, where 0 is the first campaign.

### Create a Campaign

> **This endpoint allows you to create a campaign.**<br/>
> <br/>
> Our Marketing Campaigns API lets you create, manage, send, and schedule campaigns.<br/>
> <br/>
> Note: In order to send or schedule the campaign, you will be required to provide a subject, sender ID, content (we suggest both html and plain text), and at least one list or segment ID. This information is not required when you create a campaign.<br/>
> <br/>
> For more information:<br/>
> <br/>
> * [User Guide > Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html)

*Tags:* `Campaigns API`

### Delete a Campaign

> **This endpoint allows you to delete a specific campaign.**<br/>
> <br/>
> Our Marketing Campaigns API lets you create, manage, send, and schedule campaigns.<br/>
> <br/>
> For more information:<br/>
> <br/>
> * [User Guide > Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html)

*Tags:* `Campaigns API`

#### Input Parameters
* `campaign_id` - _required_ - The id of the campaign you would like to retrieve.

### Retrieve a single campaign

> **This endpoint allows you to retrieve a specific campaign.**<br/>
> <br/>
> Our Marketing Campaigns API lets you create, manage, send, and schedule campaigns.<br/>
> <br/>
> For more information:<br/>
> <br/>
> * [User Guide > Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html)

*Tags:* `Campaigns API`

#### Input Parameters
* `campaign_id` - _required_ - The id of the campaign you would like to retrieve.

### Update a Campaign

> Update a campaign. This is especially useful if you only set up the campaign using POST /campaigns, but didn't set many of the parameters.<br/>
> <br/>
> For more information:<br/>
> <br/>
> * [User Guide > Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html)

*Tags:* `Campaigns API`

#### Input Parameters
* `campaign_id` - _required_ - The id of the campaign you would like to retrieve.

### Unschedule a Scheduled Campaign

> **This endpoint allows you to unschedule a campaign that has already been scheduled to be sent.**<br/>
> <br/>
> A successful unschedule will return a 204.<br/>
> If the specified campaign is in the process of being sent, the only option is to cancel (a different method).<br/>
> <br/>
> For more information:<br/>
> <br/>
> * [User Guide > Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html)

*Tags:* `Campaigns API`

#### Input Parameters
* `campaign_id` - _required_

### View Scheduled Time of a Campaign

> **This endpoint allows you to retrieve the date and time that the given campaign has been scheduled to be sent.**<br/>
> <br/>
> For more information:<br/>
> <br/>
> * [User Guide > Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html)

*Tags:* `Campaigns API`

#### Input Parameters
* `campaign_id` - _required_

### Update a Scheduled Campaign

> **This endpoint allows to you change the scheduled time and date for a campaign to be sent.**<br/>
> <br/>
> For more information:<br/>
> <br/>
> * [User Guide > Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html)

*Tags:* `Campaigns API`

#### Input Parameters
* `campaign_id` - _required_

### Schedule a Campaign

> **This endpoint allows you to schedule a specific date and time for your campaign to be sent.**<br/>
> <br/>
> For more information:<br/>
> <br/>
> * [User Guide > Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html)

*Tags:* `Campaigns API`

#### Input Parameters
* `campaign_id` - _required_

### Send a Campaign

> **This endpoint allows you to immediately send a campaign at the time you make the API call.**<br/>
> <br/>
> Normally a POST would have a request body, but since this endpoint is telling us to send a resource that is already created, a request body is not needed.<br/>
> <br/>
> For more information:<br/>
> <br/>
> * [User Guide > Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html)

*Tags:* `Campaigns API`

#### Input Parameters
* `campaign_id` - _required_

### Send a Test Campaign

> **This endpoint allows you to send a test campaign.**<br/>
> <br/>
> To send to multiple addresses, use an array for the JSON "to" value ["one@address","two@address"]<br/>
> <br/>
> For more information:<br/>
> <br/>
> * [User Guide > Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html)

*Tags:* `Campaigns API`

#### Input Parameters
* `campaign_id` - _required_

### Retrieve all categories

> **This endpoint allows you to retrieve a list of all of your categories.**<br/>
> <br/>
> Categories can help organize your email analytics by enabling you to "tag" emails by type or broad topic. You can define your own custom categories. For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Statistics/categories.html).

*Tags:* `Categories`

#### Input Parameters
* `limit` - _optional_ - The number of categories to display per page.
* `category` - _optional_ - Allows you to perform a prefix search on this particular category.
* `offset` - _optional_ - The point in the list that you would like to begin displaying results.
* `on-behalf-of` - _optional_

### Retrieve Email Statistics for Categories

> **This endpoint allows you to retrieve all of your email statistics for each of your categories.**<br/>
> <br/>
> If you do not define any query parameters, this endpoint will return a sum for each category in groups of 10.<br/>
> <br/>
> Categories allow you to group your emails together according to broad topics that you define. For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Statistics/categories.html).

*Tags:* `Categories`

#### Input Parameters
* `start_date` - _required_ - The starting date of the statistics to retrieve. Must follow format YYYY-MM-DD
* `end_date` - _optional_ - The end date of the statistics to retrieve. Defaults to today. Must follow format YYYY-MM-DD.
* `categories` - _required_ - The individual categories that you want to retrieve statistics for. You may include up to 10 different categories.
* `limit` - _optional_ - The number of results to include.
* `offset` - _optional_ - The number of results to skip.
* `aggregated_by` - _optional_ - How to group the statistics. Must be either "day", "week", or "month".
    Possible values: day, week, month.
* `on-behalf-of` - _optional_

### Retrieve sums of email stats for each category [Needs: Stats object defined, has category ID?]

> **This endpoint allows you to retrieve the total sum of each email statistic for every category over the given date range.**<br/>
> <br/>
> If you do not define any query parameters, this endpoint will return a sum for each category in groups of 10.<br/>
> <br/>
> Categories allow you to group your emails together according to broad topics that you define. For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Statistics/categories.html).

*Tags:* `Categories`

#### Input Parameters
* `sort_by_metric` - _optional_ - The metric that you want to sort by.  Must be a single metric.
* `sort_by_direction` - _optional_ - The direction you want to sort.
    Possible values: desc, asc.
* `start_date` - _required_ - The starting date of the statistics to retrieve. Must follow format YYYY-MM-DD.
* `end_date` - _optional_ - The end date of the statistics to retrieve. Defaults to today. Must follow format YYYY-MM-DD.
* `limit` - _optional_ - Limits the number of results returned.
* `offset` - _optional_ - The point in the list to begin retrieving results.
* `aggregated_by` - _optional_ - How to group the statistics. Must be either "day", "week", or "month".
    Possible values: day, week, month.
* `on-behalf-of` - _optional_

### Retrieve email statistics by client type.

> **This endpoint allows you to retrieve your email statistics segmented by client type.**<br/>
> <br/>
> **We only store up to 7 days of email activity in our database.** By default, 500 items will be returned per request via the Advanced Stats API endpoints.<br/>
> <br/>
> Advanced Stats provide a more in-depth view of your email statistics and the actions taken by your recipients. You can segment these statistics by geographic location, device type, client type, browser, and mailbox provider. For more information about statistics, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Statistics/index.html).

*Tags:* `Stats`

#### Input Parameters
* `start_date` - _required_ - The starting date of the statistics to retrieve. Must follow format YYYY-MM-DD.
* `end_date` - _optional_ - The end date of the statistics to retrieve. Defaults to today. Must follow format YYYY-MM-DD.
* `aggregated_by` - _optional_ - How to group the statistics. Must be either "day", "week", or "month".
    Possible values: day, week, month.
* `on-behalf-of` - _optional_

### Retrieve stats by a specific client type.

> **This endpoint allows you to retrieve your email statistics segmented by a specific client type.**<br/>
> <br/>
> **We only store up to 7 days of email activity in our database.** By default, 500 items will be returned per request via the Advanced Stats API endpoints.<br/>
> <br/>
> ## Available Client Types<br/>
> - phone<br/>
> - tablet<br/>
> - webmail<br/>
> - desktop<br/>
> <br/>
> Advanced Stats provide a more in-depth view of your email statistics and the actions taken by your recipients. You can segment these statistics by geographic location, device type, client type, browser, and mailbox provider. For more information about statistics, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Statistics/index.html).

*Tags:* `Stats`

#### Input Parameters
* `start_date` - _required_ - The starting date of the statistics to retrieve. Must follow format YYYY-MM-DD.
* `end_date` - _optional_ - The end date of the statistics to retrieve. Defaults to today. Must follow format YYYY-MM-DD.
* `aggregated_by` - _optional_ - How to group the statistics. Must be either "day", "week", or "month".
    Possible values: day, week, month.
* `on-behalf-of` - _optional_

### Retrieve all custom fields

> **This endpoint allows you to retrieve all custom fields.** <br/>
> <br/>
> The contactdb is a database of your contacts for [SendGrid Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html).

*Tags:* `Contacts API - Custom Fields`

#### Input Parameters
* `on-behalf-of` - _optional_

### Create a Custom Field

> **This endpoint allows you to create a custom field.**<br/>
> <br/>
> The contactdb is a database of your contacts for [SendGrid Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html).

*Tags:* `Contacts API - Custom Fields`

#### Input Parameters
* `on-behalf-of` - _optional_

### Delete a Custom Field

> **This endpoint allows you to delete a custom field by ID.**<br/>
> <br/>
> The contactdb is a database of your contacts for [SendGrid Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html).

*Tags:* `Contacts API - Custom Fields`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve a Custom Field

> **This endpoint allows you to retrieve a custom field by ID.**<br/>
> <br/>
> The contactdb is a database of your contacts for [SendGrid Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html).

*Tags:* `Contacts API - Custom Fields`

#### Input Parameters
* `on-behalf-of` - _optional_

### Delete Multiple lists

> **This endpoint allows you to delete multiple recipient lists.**<br/>
> <br/>
> The Contacts API helps you manage your [Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html) recipients.

*Tags:* `Contacts API - Lists`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve all lists

> **This endpoint allows you to retrieve all of your recipient lists. If you don't have any lists, an empty array will be returned.**<br/>
> <br/>
> The Contacts API helps you manage your [Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html) recipients.

*Tags:* `Contacts API - Lists`

#### Input Parameters
* `on-behalf-of` - _optional_

### Create a List

> **This endpoint allows you to create a list for your recipients.**<br/>
> <br/>
> The Contacts API helps you manage your [Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html) recipients.

*Tags:* `Contacts API - Lists`

#### Input Parameters
* `on-behalf-of` - _optional_

### Delete a List

> **This endpoint allows you to delete a specific recipient list with the given ID.**<br/>
> <br/>
> The Contacts API helps you manage your [Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html) recipients.

*Tags:* `Contacts API - Lists`

#### Input Parameters
* `delete_contacts` - _optional_ - Adds the ability to delete all contacts on the list in addition to deleting the list.
    Possible values: true, false.
* `on-behalf-of` - _optional_

### Retrieve a single list

> This endpoint allows you to retrieve a single recipient list.<br/>
> <br/>
> The Contacts API helps you manage your [Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html) recipients.

*Tags:* `Contacts API - Lists`

#### Input Parameters
* `list_id` - _optional_ - The ID of the list to retrieve.
* `on-behalf-of` - _optional_

### Update a List

> **This endpoint allows you to update the name of one of your recipient lists.**<br/>
> <br/>
> <br/>
> The Contacts API helps you manage your [Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html) recipients.

*Tags:* `Contacts API - Lists`

#### Input Parameters
* `list_id` - _required_ - The ID of the list you are updating.
* `on-behalf-of` - _optional_

### Retrieve all recipients on a List

> **This endpoint allows you to retrieve all recipients on the list with the given ID.** <br/>
> <br/>
> The Contacts API helps you manage your [Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html) recipients.

*Tags:* `Contacts API - Lists`

#### Input Parameters
* `page` - _optional_ - Page index of first recipient to return (must be a positive integer)
* `page_size` - _optional_ - Number of recipients to return at a time (must be a positive integer between 1 and 1000)
* `list_id` - _required_ - The ID of the list whose recipients you are requesting.
* `on-behalf-of` - _optional_

### Add Multiple Recipients to a List

> **This endpoint allows you to add multiple recipients to a list.**<br/>
> <br/>
> Adds existing recipients to a list, passing in the recipient IDs to add. Recipient IDs should be passed exactly as they are returned from recipient endpoints.<br/>
> <br/>
> The Contacts API helps you manage your [Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html) recipients.

*Tags:* `Contacts API - Lists`

#### Input Parameters
* `on-behalf-of` - _optional_

### Delete a Single Recipient from a Single List

> **This endpoint allows you to delete a single recipient from a list.**<br/>
> <br/>
> The Contacts API helps you manage your [Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html) recipients.

*Tags:* `Contacts API - Lists`

#### Input Parameters
* `list_id` - _required_ - The ID of the list you are taking this recipient away from.
* `recipient_id` - _required_ - The ID of the recipient to take off the list.
* `on-behalf-of` - _optional_

### Add a Single Recipient to a List

> **This endpoint allows you to add a single recipient to a list.**<br/>
> <br/>
> The Contacts API helps you manage your [Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html) recipients.

*Tags:* `Contacts API - Lists`

#### Input Parameters
* `on-behalf-of` - _optional_
* `recipient_id` - _required_ - The ID of the recipient you are adding to the list.

### Delete Recipient

> **This endpoint allows you to deletes one or more recipients.**<br/>
> <br/>
> The body of an API call to this endpoint must include an array of recipient IDs of the recipients you want to delete.<br/>
> <br/>
> The contactdb is a database of your contacts for [SendGrid Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html).

*Tags:* `Contacts API - Recipients`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve recipients

> **This endpoint allows you to retrieve all of your Marketing Campaigns recipients.**<br/>
> <br/>
> Batch deletion of a page makes it possible to receive an empty page of recipients before reaching the end of<br/>
> the list of recipients. To avoid this issue; iterate over pages until a 404 is retrieved.<br/>
> <br/>
> The Contacts API helps you manage your [Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html) recipients.

*Tags:* `Contacts API - Recipients`

#### Input Parameters
* `page` - _optional_ - Page index of first recipients to return (must be a positive integer)
* `page_size` - _optional_ - Number of recipients to return at a time (must be a positive integer between 1 and 1000)
* `on-behalf-of` - _optional_

### Update Recipient

> **This endpoint allows you to update one or more recipients.**<br/>
> <br/>
> The body of an API call to this endpoint must include an array of one or more recipient objects.<br/>
> <br/>
> It is of note that you can add custom field data as parameters on recipient objects. We have provided an example using some of the default custom fields SendGrid provides.<br/>
> <br/>
> The contactdb is a database of your contacts for [SendGrid Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html).

*Tags:* `Contacts API - Recipients`

#### Input Parameters
* `on-behalf-of` - _optional_

### Add recipients

> **This endpoint allows you to add a Marketing Campaigns recipient.**<br/>
> <br/>
> You can add custom field data as a parameter on this endpoint. We have provided an example using some of the default custom fields SendGrid provides.<br/>
> <br/>
> The Contacts API helps you manage your [Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html) recipients.

*Tags:* `Contacts API - Recipients`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve the count of billable recipients

> **This endpoint allows you to retrieve the number of Marketing Campaigns recipients that you will be billed for.**<br/>
> <br/>
> You are billed for marketing campaigns based on the highest number of recipients you have had in your account at one time. This endpoint will allow you to know the current billable count value.<br/>
> <br/>
> The Contacts API helps you manage your [Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html) recipients.

*Tags:* `Contacts API - Recipients`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve a Count of Recipients

> **This endpoint allows you to retrieve the total number of Marketing Campaigns recipients.**<br/>
> <br/>
> The contactdb is a database of your contacts for [SendGrid Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html).

*Tags:* `Contacts API - Recipients`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve recipients matching search criteria

> **This endpoint allows you to perform a search on all of your Marketing Campaigns recipients.**<br/>
> <br/>
> field_name:<br/>
> <br/>
> * is a variable that is substituted for your actual custom field name from your recipient.<br/>
> * Text fields must be url-encoded. Date fields are searchable only by unix timestamp (e.g. 2/2/2015 becomes 1422835200)<br/>
> * If field_name is a 'reserved' date field, such as created_at or updated_at, the system will internally convert<br/>
> your epoch time to a date range encompassing the entire day. For example, an epoch time of 1422835600 converts to<br/>
> Mon, 02 Feb 2015 00:06:40 GMT, but internally the system will search from Mon, 02 Feb 2015 00:00:00 GMT through<br/>
> Mon, 02 Feb 2015 23:59:59 GMT.<br/>
> <br/>
> The contactdb is a database of your contacts for [SendGrid Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html).

*Tags:* `Contacts API - Recipients`

#### Input Parameters
* `{field_name}` - _optional_
* `on-behalf-of` - _optional_

### Delete a Recipient

> **This endpoint allows you to delete a single recipient with the given ID from your contact database.**<br/>
> <br/>
> The Contacts API helps you manage your [Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html) recipients.

*Tags:* `Contacts API - Recipients`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve a single recipient

> **This endpoint allows you to retrieve a single recipient by ID from your contact database.**<br/>
> <br/>
> The Contacts API helps you manage your [Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html) recipients.

*Tags:* `Contacts API - Recipients`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve the lists that a recipient is on

> **This endpoint allows you to retrieve the lists that a given recipient belongs to.**<br/>
> <br/>
> Each recipient can be on many lists. This endpoint gives you all of the lists that any one recipient has been added to.<br/>
> <br/>
> The Contacts API helps you manage your [Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html) recipients.

*Tags:* `Contacts API - Recipients`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve reserved fields

> **This endpoint allows you to list all fields that are reserved and can't be used for custom field names.**<br/>
> <br/>
> The contactdb is a database of your contacts for [SendGrid Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html).

*Tags:* `Contacts API - Custom Fields`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve all segments

> **This endpoint allows you to retrieve all of your segments.**<br/>
> <br/>
> The Contacts API helps you manage your [Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html) recipients.<br/>
> <br/>
> For more information about segments in Marketing Campaigns, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/lists.html#-Create-a-Segment).

*Tags:* `Contacts API - Segments`

#### Input Parameters
* `on-behalf-of` - _optional_

### Create a Segment

> **This endpoint allows you to create a segment.**<br/>
> <br/>
> All recipients in your contactdb will be added or removed automatically depending on whether they match the criteria for this segment.<br/>
> <br/>
> List Id:<br/>
> <br/>
> * Send this to segment from an existing list<br/>
> * Don't send this in order to segment from your entire contactdb.<br/>
> <br/>
> Valid operators for create and update depend on the type of the field you are segmenting: <br/>
> <br/>
> * **Dates:** "eq", "ne", "lt" (before), "gt" (after) <br/>
> * **Text:** "contains", "eq" (is - matches the full field), "ne" (is not - matches any field where the entire field is not the condition value) <br/>
> * **Numbers:** "eq", "lt", "gt" <br/>
> * **Email Clicks and Opens:** "eq" (opened), "ne" (not opened) <br/>
> <br/>
> Segment conditions using "eq" or "ne" for email clicks and opens should provide a "field" of either *clicks.campaign_identifier* or *opens.campaign_identifier*. The condition value should be a string containing the id of a completed campaign. <br/>
> <br/>
> Segments may contain multiple condtions, joined by an "and" or "or" in the "and_or" field. The first condition in the conditions list must have an empty "and_or", and subsequent conditions must all specify an "and_or".<br/>
> <br/>
> The Contacts API helps you manage your [Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html) recipients.<br/>
> <br/>
> For more information about segments in Marketing Campaigns, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/lists.html#-Create-a-Segment).

*Tags:* `Contacts API - Segments`

#### Input Parameters
* `on-behalf-of` - _optional_

### Delete a segment

> **This endpoint allows you to delete a segment from your recipients database.**<br/>
> <br/>
> You also have the option to delete all the contacts from your Marketing Campaigns recipient database who were in this segment.<br/>
> <br/>
> The Contacts API helps you manage your [Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html) recipients.<br/>
> <br/>
> For more information about segments in Marketing Campaigns, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/lists.html#-Create-a-Segment).

*Tags:* `Contacts API - Segments`

#### Input Parameters
* `delete_contacts` - _optional_ - True to delete all contacts matching the segment in addition to deleting the segment
* `on-behalf-of` - _optional_

### Retrieve a segment

> **This endpoint allows you to retrieve a single segment with the given ID.**<br/>
> <br/>
> The Contacts API helps you manage your [Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html) recipients.<br/>
> <br/>
> For more information about segments in Marketing Campaigns, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/lists.html#-Create-a-Segment).

*Tags:* `Contacts API - Segments`

#### Input Parameters
* `segment_id` - _required_ - The ID of the segment you want to request.
* `on-behalf-of` - _optional_

### Update a segment

> **This endpoint allows you to update a segment.**<br/>
> <br/>
> The Contacts API helps you manage your [Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html) recipients.<br/>
> <br/>
> For more information about segments in Marketing Campaigns, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/lists.html#-Create-a-Segment).

*Tags:* `Contacts API - Segments`

#### Input Parameters
* `segment_id` - _optional_ - The ID of the segment you are updating.
* `on-behalf-of` - _optional_

### Retrieve recipients on a segment

> **This endpoint allows you to retrieve all of the recipients in a segment with the given ID.**<br/>
> <br/>
> The Contacts API helps you manage your [Marketing Campaigns](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/index.html) recipients.<br/>
> <br/>
> For more information about segments in Marketing Campaigns, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/lists.html#-Create-a-Segment).

*Tags:* `Contacts API - Segments`

#### Input Parameters
* `page` - _optional_
* `page_size` - _optional_
* `on-behalf-of` - _optional_

### Get Contact Upload Status

*Tags:* `Contacts API - Recipients`

#### Input Parameters
* `Authorization` - _required_
* `on-behalf-of` - _optional_

### Retrieve email statistics by device type.

> **This endpoint allows you to retrieve your email statistics segmented by the device type.**<br/>
> <br/>
> **We only store up to 7 days of email activity in our database.** By default, 500 items will be returned per request via the Advanced Stats API endpoints.<br/>
> <br/>
> ## Available Device Types<br/>
> | **Device** | **Description** | **Example** |<br/>
> |---|---|---|<br/>
> | Desktop | Email software on desktop computer. | I.E., Outlook, Sparrow, or Apple Mail. |<br/>
> | Webmail |	A web-based email client. | I.E., Yahoo, Google, AOL, or Outlook.com. |<br/>
> | Phone | A smart phone. | iPhone, Android, Blackberry, etc.<br/>
> | Tablet | A tablet computer. | iPad, android based tablet, etc. |<br/>
> | Other | An unrecognized device. |<br/>
> <br/>
> Advanced Stats provide a more in-depth view of your email statistics and the actions taken by your recipients. You can segment these statistics by geographic location, device type, client type, browser, and mailbox provider. For more information about statistics, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Statistics/index.html).

*Tags:* `Stats`

#### Input Parameters
* `end_date` - _optional_ - The end date of the statistics to retrieve. Defaults to today.
* `limit` - _optional_ - How many results to include on each page.
* `offset` - _optional_ - How many results to exclude.
* `aggregated_by` - _optional_ - How to group the statistics. Must be either "day", "week", or "month".
* `start_date` - _required_ - The starting date of the statistics to retrieve.
* `on-behalf-of` - _optional_

### Retrieve email statistics by country and state/province.

> **This endpoint allows you to retrieve your email statistics segmented by country and state/province.**<br/>
> <br/>
> **We only store up to 7 days of email activity in our database.** By default, 500 items will be returned per request via the Advanced Stats API endpoints.<br/>
> <br/>
> Advanced Stats provide a more in-depth view of your email statistics and the actions taken by your recipients. You can segment these statistics by geographic location, device type, client type, browser, and mailbox provider. For more information about statistics, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Statistics/index.html).

*Tags:* `Stats`

#### Input Parameters
* `limit` - _optional_ - How many results to include on each page.
* `offset` - _optional_ - How many results to exclude.
* `aggregated_by` - _optional_ - How you would like the statistics to be grouped. Must be either "day", "week", or "month".
    Possible values: day, week, month.
* `start_date` - _required_ - The starting date of the statistics to retrieve. Must be in format YYYY-MM-DD
* `end_date` - _optional_ - The end date of the statistics to retrieve. 
* `country` - _optional_ - The country you would like to see statistics for. Currently only supported for US and CA.
    Possible values: US, CA.
* `Authorization` - _required_
* `on-behalf-of` - _optional_

### Retrieve all IP addresses

> **This endpoint allows you to retrieve a list of all assigned and unassigned IPs.**<br/>
> <br/>
> Response includes warm up status, pools, assigned subusers, and whitelabel info. The start_date field corresponds to when warmup started for that IP.<br/>
> <br/>
> A single IP address or a range of IP addresses may be dedicated to an account in order to send email for multiple domains. The reputation of this IP is based on the aggregate performance of all the senders who use it.

*Tags:* `IP Addresses`

#### Input Parameters
* `ip` - _optional_ - The IP address to get
* `exclude_whitelabels` - _optional_ - Should we exclude whitelabels?
* `limit` - _optional_ - The number of IPs you want returned at the same time.
* `offset` - _optional_ - The offset for the number of IPs that you are requesting.
* `subuser` - _optional_ - The subuser you are requesting for.
* `sort_by_direction` - _optional_ - The direction to sort the results.
    Possible values: desc, asc.

### Add IPs

> This endpoint is for adding a(n) IP Address(es) to your account.

*Tags:* `IP Addresses`

### Retrieve all assigned IPs

> **This endpoint allows you to retrieve only assigned IP addresses.**<br/>
> <br/>
> A single IP address or a range of IP addresses may be dedicated to an account in order to send email for multiple domains. The reputation of this IP is based on the aggregate performance of all the senders who use it.

*Tags:* `IP Addresses`

### Retrieve all IP pools.

> **This endpoint allows you to retreive all of your IP pools.**<br/>
> <br/>
> IP Pools allow you to group your dedicated SendGrid IP addresses together. For example, you could create separate pools for your transactional and marketing email. When sending marketing emails, specify that you want to use the marketing IP pool. This allows you to maintain separate reputations for your different email traffic.<br/>
> <br/>
> IP pools can only be used with whitelabeled IP addresses.<br/>
> <br/>
> If an IP pool is NOT specified for an email, it will use any IP available, including ones in pools.

*Tags:* `IP Pools`

### Create an IP pool.

> **This endpoint allows you to create an IP pool.**<br/>
> <br/>
> **Each user can create up to 10 different IP pools.**<br/>
> <br/>
> IP Pools allow you to group your dedicated SendGrid IP addresses together. For example, you could create separate pools for your transactional and marketing email. When sending marketing emails, specify that you want to use the marketing IP pool. This allows you to maintain separate reputations for your different email traffic.<br/>
> <br/>
> IP pools can only be used with whitelabeled IP addresses.<br/>
> <br/>
> If an IP pool is NOT specified for an email, it will use any IP available, including ones in pools.

*Tags:* `IP Pools`

### Delete an IP pool.

> **This endpoint allows you to delete an IP pool.**<br/>
> <br/>
> IP Pools allow you to group your dedicated SendGrid IP addresses together. For example, you could create separate pools for your transactional and marketing email. When sending marketing emails, specify that you want to use the marketing IP pool. This allows you to maintain separate reputations for your different email traffic.<br/>
> <br/>
> IP pools can only be used with whitelabeled IP addresses.<br/>
> <br/>
> If an IP pool is NOT specified for an email, it will use any IP available, including ones in pools.

*Tags:* `IP Pools`

#### Input Parameters
* `pool_name` - _required_ - The name of the IP pool that you want to retrieve the IP addresses from.

### Retrieve all IPs in a specified pool.

> **This endpoint allows you to list all of the IP addresses that are in a specific IP pool.**<br/>
> <br/>
> IP Pools allow you to group your dedicated SendGrid IP addresses together. For example, you could create separate pools for your transactional and marketing email. When sending marketing emails, specify that you want to use the marketing IP pool. This allows you to maintain separate reputations for your different email traffic.<br/>
> <br/>
> IP pools can only be used with whitelabeled IP addresses.<br/>
> <br/>
> If an IP pool is NOT specified for an email, it will use any IP available, including ones in pools.

*Tags:* `IP Pools`

#### Input Parameters
* `pool_name` - _required_ - The name of the IP pool that you want to retrieve the IP addresses from.

### Update an IP pool's name.

> **This endpoint allows you to update the name of an IP pool.**<br/>
> <br/>
> IP Pools allow you to group your dedicated SendGrid IP addresses together. For example, you could create separate pools for your transactional and marketing email. When sending marketing emails, specify that you want to use the marketing IP pool. This allows you to maintain separate reputations for your different email traffic.<br/>
> <br/>
> IP pools can only be used with whitelabeled IP addresses.<br/>
> <br/>
> If an IP pool is NOT specified for an email, it will use any IP available, including ones in pools.

*Tags:* `IP Pools`

#### Input Parameters
* `pool_name` - _required_ - The name of the IP pool that you want to retrieve the IP addresses from.

### Add an IP address to a pool

> **This endpoint allows you to add an IP address to an IP pool.**<br/>
> <br/>
> You can add the same IP address to multiple pools. It may take up to 60 seconds for your IP address to be added to a pool after your request is made.<br/>
> <br/>
> A single IP address or a range of IP addresses may be dedicated to an account in order to send email for multiple domains. The reputation of this IP is based on the aggregate performance of all the senders who use it.

*Tags:* `IP Pools`

#### Input Parameters
* `pool_name` - _required_ - The name of the IP pool that you want to add an IP address to.

### Remove an IP address from a pool.

> **This endpoint allows you to remove an IP address from an IP pool.**<br/>
> <br/>
> The same IP address can be added to multiple IP pools.<br/>
> <br/>
> A single IP address or a range of IP addresses may be dedicated to an account in order to send email for multiple domains. The reputation of this IP is based on the aggregate performance of all the senders who use it.

*Tags:* `IP Pools`

#### Input Parameters
* `pool_name` - _required_ - The name of the IP pool that you are removing the IP address from.
* `ip` - _required_ - The IP address that you are removing.

### Get remaining IPs count

> This endpoint gets amount of IP Addresses that can still be created during a given period and the price of those IPs.

*Tags:* `IP Addresses`

### Retrieve all IPs currently in warmup

> **This endpoint allows you to retrieve all of your IP addresses that are currently warming up.**<br/>
> <br/>
> SendGrid can automatically warm up dedicated IP addresses by limiting the amount of mail that can be sent through them per hour, with the limit determined by how long the IP address has been in warmup. See the [warmup schedule](https://sendgrid.com/docs/API_Reference/Web_API_v3/IP_Management/ip_warmup_schedule.html) for more details on how SendGrid limits your email traffic for IPs in warmup.<br/>
> <br/>
> For more general information about warming up IPs, please see our [Classroom](https://sendgrid.com/docs/Classroom/Deliver/Delivery_Introduction/warming_up_ips.html).

*Tags:* `IP Warmup`

#### Input Parameters
* `on-behalf-of` - _optional_

### Add an IP to warmup

> **This endpoint allows you to enter an IP address into warmup mode.**<br/>
> <br/>
> SendGrid can automatically warm up dedicated IP addresses by limiting the amount of mail that can be sent through them per hour, with the limit determined by how long the IP address has been in warmup. See the [warmup schedule](https://sendgrid.com/docs/API_Reference/Web_API_v3/IP_Management/ip_warmup_schedule.html) for more details on how SendGrid limits your email traffic for IPs in warmup.<br/>
> <br/>
> For more general information about warming up IPs, please see our [Classroom](https://sendgrid.com/docs/Classroom/Deliver/Delivery_Introduction/warming_up_ips.html).

*Tags:* `IP Warmup`

#### Input Parameters
* `on-behalf-of` - _optional_

### Remove an IP from warmup

> **This endpoint allows you to remove an IP address from warmup mode.**<br/>
> <br/>
> SendGrid can automatically warm up dedicated IP addresses by limiting the amount of mail that can be sent through them per hour, with the limit determined by how long the IP address has been in warmup. See the [warmup schedule](https://sendgrid.com/docs/API_Reference/Web_API_v3/IP_Management/ip_warmup_schedule.html) for more details on how SendGrid limits your email traffic for IPs in warmup.<br/>
> <br/>
> For more general information about warming up IPs, please see our [Classroom](https://sendgrid.com/docs/Classroom/Deliver/Delivery_Introduction/warming_up_ips.html).

*Tags:* `IP Warmup`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve warmup status for a specific IP address

> **This endpoint allows you to retrieve the warmup status for a specific IP address.**<br/>
> <br/>
> SendGrid can automatically warm up dedicated IP addresses by limiting the amount of mail that can be sent through them per hour, with the limit determined by how long the IP address has been in warmup. See the [warmup schedule](https://sendgrid.com/docs/API_Reference/Web_API_v3/IP_Management/ip_warmup_schedule.html) for more details on how SendGrid limits your email traffic for IPs in warmup.<br/>
> <br/>
> For more general information about warming up IPs, please see our [Classroom](https://sendgrid.com/docs/Classroom/Deliver/Delivery_Introduction/warming_up_ips.html).

*Tags:* `IP Warmup`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve all IP pools an IP address belongs to

> **This endpoint allows you to see which IP pools a particular IP address has been added to.**<br/>
> <br/>
> The same IP address can be added to multiple IP pools.<br/>
> <br/>
> A single IP address or a range of IP addresses may be dedicated to an account in order to send email for multiple domains. The reputation of this IP is based on the aggregate performance of all the senders who use it.

*Tags:* `IP Addresses`

#### Input Parameters
* `ip_address` - _required_ - The IP address you are retrieving the IP pools for.

### Create a batch ID

> **This endpoint allows you to generate a new batch ID. This batch ID can be associated with scheduled sends via the mail/send endpoint.**<br/>
> <br/>
> If you set the SMTPAPI header `batch_id`, it allows you to then associate multiple scheduled mail/send requests together with the same ID. Then at anytime up to 10 minutes before the schedule date, you can cancel all of the mail/send requests that have this batch ID by calling the Cancel Scheduled Send endpoint. <br/>
> <br/>
> More Information:<br/>
> <br/>
> * [Scheduling Parameters > Batch ID](https://sendgrid.com/docs/API_Reference/SMTP_API/scheduling_parameters.html)

*Tags:* `Cancel Scheduled Sends`

### Validate batch ID

> **This endpoint allows you to validate a batch ID.**<br/>
> <br/>
> If you set the SMTPAPI header `batch_id`, it allows you to then associate multiple scheduled mail/send requests together with the same ID. Then at anytime up to 10 minutes before the schedule date, you can cancel all of the mail/send requests that have this batch ID by calling the Cancel Scheduled Send endpoint. <br/>
> <br/>
> More Information:<br/>
> <br/>
> * [Scheduling Parameters > Batch ID](https://sendgrid.com/docs/API_Reference/SMTP_API/scheduling_parameters.html)

*Tags:* `Cancel Scheduled Sends`

#### Input Parameters
* `batch_id` - _required_

### v3 Mail Send

> This endpoint allows you to send email over SendGrid's v3 Web API, the most recent version of our API. If you are looking for documentation about the v2 Mail Send endpoint, please see our [v2 API Reference](https://sendgrid.com/docs/API_Reference/Web_API/mail.html).<br/>
> <br/>
> * Top level parameters are referred to as "global".<br/>
> * Individual fields within the personalizations array will override any other global, or "message level", parameters that are defined outside of personalizations.<br/>
>  <br/>
> **SendGrid provides libraries to help you quickly and easily integrate with the v3 Web API in 7 different languages: [C#](https://github.com/sendgrid/sendgrid-csharp), [Go](https://github.com/sendgrid/sendgrid-go), [Java](https://github.com/sendgrid/sendgrid-java), [Node JS](https://github.com/sendgrid/sendgrid-nodejs), [PHP](https://github.com/sendgrid/sendgrid-php), [Python](https://github.com/sendgrid/sendgrid-python), and [Ruby](https://github.com/sendgrid/sendgrid-ruby).**<br/>
> <br/>
> <br/>
> For more detailed information about how to use the v3 Mail Send endpoint, please visit our [Classroom](https://sendgrid.com/docs/Classroom/Send/v3_Mail_Send/index.html).

*Tags:* `Mail Send`

### Retrieve all mail settings

> **This endpoint allows you to retrieve a list of all mail settings.**<br/>
> <br/>
> Mail settings allow you to tell SendGrid specific things to do to every email that you send to your recipients over SendGrid's [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html) or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html).

*Tags:* `Settings - Mail`

#### Input Parameters
* `limit` - _optional_ - The number of settings to return.
* `offset` - _optional_ - Where in the list of results to begin displaying settings.
* `on-behalf-of` - _optional_

### Retrieve address whitelist mail settings

> **This endpoint allows you to retrieve your current email address whitelist settings.**<br/>
> <br/>
> The address whitelist setting whitelists a specified email address or domain for which mail should never be suppressed. For example, you own the domain "example.com," and one or more of your recipients use email@example.com addresses, by placing example.com in the address whitelist setting, all bounces, blocks, and unsubscribes logged for that domain will be ignored and sent as if under normal sending conditions.<br/>
> <br/>
> Mail settings allow you to tell SendGrid specific things to do to every email that you send to your recipients over SendGrid's [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html) or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html).

*Tags:* `Settings - Mail`

#### Input Parameters
* `on-behalf-of` - _optional_

### Update address whitelist mail settings

> **This endpoint allows you to update your current email address whitelist settings.**<br/>
> <br/>
> The address whitelist setting whitelists a specified email address or domain for which mail should never be suppressed. For example, you own the domain "example.com," and one or more of your recipients use email@example.com addresses, by placing example.com in the address whitelist setting, all bounces, blocks, and unsubscribes logged for that domain will be ignored and sent as if under normal sending conditions.<br/>
> <br/>
> Mail settings allow you to tell SendGrid specific things to do to every email that you send to your recipients over SendGrid's [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html) or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html).

*Tags:* `Settings - Mail`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve all BCC mail settings

> **This endpoint allows you to retrieve your current BCC mail settings.**<br/>
> <br/>
> When the BCC mail setting is enabled, SendGrid will automatically send a blind carbon copy (BCC) to an address for every email sent without adding that address to the header. Please note that only one email address may be entered in this field, if you wish to distribute BCCs to multiple addresses you will need to create a distribution group or use forwarding rules.<br/>
> <br/>
> Mail settings allow you to tell SendGrid specific things to do to every email that you send to your recipients over SendGrid's [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html) or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html).

*Tags:* `Settings - Mail`

#### Input Parameters
* `on-behalf-of` - _optional_

### Update BCC mail settings

> **This endpoint allows you to update your current BCC mail settings.**<br/>
> <br/>
> When the BCC mail setting is enabled, SendGrid will automatically send a blind carbon copy (BCC) to an address for every email sent without adding that address to the header. Please note that only one email address may be entered in this field, if you wish to distribute BCCs to multiple addresses you will need to create a distribution group or use forwarding rules.<br/>
> <br/>
> Mail settings allow you to tell SendGrid specific things to do to every email that you send to your recipients over SendGrid's [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html) or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html).

*Tags:* `Settings - Mail`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve bounce purge mail settings

> **This endpoint allows you to retrieve your current bounce purge settings.**<br/>
> <br/>
> This setting allows you to set a schedule for SendGrid to automatically delete contacts from your soft and hard bounce suppression lists.<br/>
> <br/>
> Mail settings allow you to tell SendGrid specific things to do to every email that you send to your recipients over SendGrid's [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html) or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html).

*Tags:* `Settings - Mail`

#### Input Parameters
* `on-behalf-of` - _optional_

### Update bounce purge mail settings

> **This endpoint allows you to update your current bounce purge settings.**<br/>
> <br/>
> This setting allows you to set a schedule for SendGrid to automatically delete contacts from your soft and hard bounce suppression lists.<br/>
> <br/>
> Mail settings allow you to tell SendGrid specific things to do to every email that you send to your recipients over SendGrid's [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html) or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html).

*Tags:* `Settings - Mail`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve footer mail settings

> **This endpoint allows you to retrieve your current Footer mail settings.**<br/>
> <br/>
> The footer setting will insert a custom footer at the bottom of the text and HTML bodies. Use the embedded HTML editor and plain text entry fields to create the content of the footers to be inserted into your emails.<br/>
> <br/>
> Mail settings allow you to tell SendGrid specific things to do to every email that you send to your recipients over SendGrid's [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html) or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html).

*Tags:* `Settings - Mail`

#### Input Parameters
* `on-behalf-of` - _optional_

### Update footer mail settings

> **This endpoint allows you to update your current Footer mail settings.**<br/>
> <br/>
> The footer setting will insert a custom footer at the bottom of the text and HTML bodies. Use the embedded HTML editor and plain text entry fields to create the content of the footers to be inserted into your emails.<br/>
> <br/>
> Mail settings allow you to tell SendGrid specific things to do to every email that you send to your recipients over SendGrid's [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html) or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html).

*Tags:* `Settings - Mail`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve forward bounce mail settings

> **This endpoint allows you to retrieve your current bounce forwarding mail settings.**<br/>
> <br/>
> Activating this setting allows you to specify an email address to which bounce reports are forwarded.<br/>
> <br/>
> Mail settings allow you to tell SendGrid specific things to do to every email that you send to your recipients over SendGrid's [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html) or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html).

*Tags:* `Settings - Mail`

#### Input Parameters
* `on-behalf-of` - _optional_

### Update forward bounce mail settings

> **This endpoint allows you to update your current bounce forwarding mail settings.**<br/>
> <br/>
> Activating this setting allows you to specify an email address to which bounce reports are forwarded.<br/>
> <br/>
> Mail settings allow you to tell SendGrid specific things to do to every email that you send to your recipients over SendGrid's [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html) or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html).

*Tags:* `Settings - Mail`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve forward spam mail settings

> **This endpoint allows you to retrieve your current Forward Spam mail settings.**<br/>
> <br/>
> Enabling the forward spam setting allows you to specify an email address to which spam reports will be forwarded.<br/>
> <br/>
> Mail settings allow you to tell SendGrid specific things to do to every email that you send to your recipients over SendGrid's [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html) or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html).

*Tags:* `Settings - Mail`

#### Input Parameters
* `on-behalf-of` - _optional_

### Update forward spam mail settings

> **This endpoint allows you to update your current Forward Spam mail settings.**<br/>
> <br/>
> Enabling the forward spam setting allows you to specify an email address to which spam reports will be forwarded.<br/>
> <br/>
> Mail settings allow you to tell SendGrid specific things to do to every email that you send to your recipients over SendGrid's [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html) or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html).

*Tags:* `Settings - Mail`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve plain content mail settings

> **This endpoint allows you to retrieve your current Plain Content mail settings.**<br/>
> <br/>
> The plain content setting will automatically convert any plain text emails that you send to HTML before sending.<br/>
> <br/>
> Mail settings allow you to tell SendGrid specific things to do to every email that you send to your recipients over SendGrid's [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html) or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html).

*Tags:* `Settings - Mail`

#### Input Parameters
* `on-behalf-of` - _optional_

### Update plain content mail settings

> **This endpoint allows you to update your current Plain Content mail settings.**<br/>
> <br/>
> The plain content setting will automatically convert any plain text emails that you send to HTML before sending.<br/>
> <br/>
> Mail settings allow you to tell SendGrid specific things to do to every email that you send to your recipients over SendGrid's [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html) or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html).

*Tags:* `Settings - Mail`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve spam check mail settings

> **This endpoint allows you to retrieve your current Spam Checker mail settings.**<br/>
> <br/>
> The spam checker filter notifies you when emails are detected that exceed a predefined spam threshold.<br/>
> <br/>
> Mail settings allow you to tell SendGrid specific things to do to every email that you send to your recipients over SendGrid's [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html) or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html).

*Tags:* `Settings - Mail`

#### Input Parameters
* `on-behalf-of` - _optional_

### Update spam check mail settings

> **This endpoint allows you to update your current spam checker mail settings.**<br/>
> <br/>
> The spam checker filter notifies you when emails are detected that exceed a predefined spam threshold.<br/>
> <br/>
> Mail settings allow you to tell SendGrid specific things to do to every email that you send to your recipients over SendGrid's [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html) or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html).

*Tags:* `Settings - Mail`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve legacy template mail settings

> **This endpoint allows you to retrieve your current legacy email template settings.**<br/>
> <br/>
> This setting refers to our original email templates. We currently support more fully featured [transactional templates](https://sendgrid.com/docs/User_Guide/Transactional_Templates/index.html). <br/>
> <br/>
> The legacy email template setting wraps an HTML template around your email content. This can be useful for sending out marketing email and/or other HTML formatted messages.<br/>
> <br/>
> Mail settings allow you to tell SendGrid specific things to do to every email that you send to your recipients over SendGrid's [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html) or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html).

*Tags:* `Settings - Mail`

#### Input Parameters
* `on-behalf-of` - _optional_

### Update template mail settings

> **This endpoint allows you to update your current legacy email template settings.**<br/>
> <br/>
> This setting refers to our original email templates. We currently support more fully featured [transactional templates](https://sendgrid.com/docs/User_Guide/Transactional_Templates/index.html). <br/>
> <br/>
> The legacy email template setting wraps an HTML template around your email content. This can be useful for sending out marketing email and/or other HTML formatted messages.<br/>
> <br/>
> Mail settings allow you to tell SendGrid specific things to do to every email that you send to your recipients over SendGrid's [Web API](https://sendgrid.com/docs/API_Reference/Web_API/mail.html) or [SMTP Relay](https://sendgrid.com/docs/API_Reference/SMTP_API/index.html).

*Tags:* `Settings - Mail`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve email statistics by mailbox provider.

> **This endpoint allows you to retrieve your email statistics segmented by recipient mailbox provider.**<br/>
> <br/>
> **We only store up to 7 days of email activity in our database.** By default, 500 items will be returned per request via the Advanced Stats API endpoints.<br/>
> <br/>
> Advanced Stats provide a more in-depth view of your email statistics and the actions taken by your recipients. You can segment these statistics by geographic location, device type, client type, browser, and mailbox provider. For more information about statistics, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Statistics/index.html).

*Tags:* `Stats`

#### Input Parameters
* `limit` - _optional_ - The number of results to include on each page.
* `offset` - _optional_ - The number of results to exclude.
* `aggregated_by` - _optional_ - How to group the stats. Must be either "day", "wee", or "month".
    Possible values: day, week, month.
* `start_date` - _required_ - The starting date of the statistics to retrieve. Must follow format YYYY-MM-DD.
* `end_date` - _optional_ - The end date of the statistics to retrieve. Defaults to today. Must follow format YYYY-MM-DD.
* `mailbox_providers` - _optional_ - The mail box providers to get statistics for. You can include up to 10 by including this parameter multiple times.
* `on-behalf-of` - _optional_

### Returns a list of all partner settings.

> **This endpoint allows you to retrieve a list of all partner settings that you can enable.**<br/>
> <br/>
> Our partner settings allow you to integrate your SendGrid account with our partners to increase your SendGrid experience and functionality. For more information about our partners, and how you can begin integrating with them, please visit our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/partners.html).

*Tags:* `Settings - Partner`

#### Input Parameters
* `limit` - _optional_ - The number of settings to return per page.
* `offset` - _optional_ - The paging offset.

### Returns all New Relic partner settings.

> **This endpoint allows you to retrieve your current New Relic partner settings.**<br/>
> <br/>
> Our partner settings allow you to integrate your SendGrid account with our partners to increase your SendGrid experience and functionality. For more information about our partners, and how you can begin integrating with them, please visit our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/partners.html).<br/>
> <br/>
> By integrating with New Relic, you can send your SendGrid email statistics to your New Relic Dashboard. If you enable this setting, your stats will be sent to New Relic every 5 minutes. You will need your New Relic License Key to enable this setting. For more information, please see our [Classroom](https://sendgrid.com/docs/Classroom/Track/Collecting_Data/new_relic.html).

*Tags:* `Settings - Partner`

### Updates New Relic partner settings.

> **This endpoint allows you to update or change your New Relic partner settings.**<br/>
> <br/>
> Our partner settings allow you to integrate your SendGrid account with our partners to increase your SendGrid experience and functionality. For more information about our partners, and how you can begin integrating with them, please visit our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/partners.html).<br/>
> <br/>
> By integrating with New Relic, you can send your SendGrid email statistics to your New Relic Dashboard. If you enable this setting, your stats will be sent to New Relic every 5 minutes. You will need your New Relic License Key to enable this setting. For more information, please see our [Classroom](https://sendgrid.com/docs/Classroom/Track/Collecting_Data/new_relic.html).

*Tags:* `Settings - Partner`

### Retrieve a list of scopes for which this user has access.

> **This endpoint returns a list of all scopes that this user has access to.**<br/>
> <br/>
> API Keys can be used to authenticate the use of [SendGrid's v3 Web API](https://sendgrid.com/docs/API_Reference/Web_API_v3/index.html), or the [Mail API Endpoint](https://sendgrid.com/docs/API_Reference/Web_API/mail.html). API Keys may be assigned certain permissions, or scopes, that limit which API endpoints they are able to access. For a more detailed explanation of how you can use API Key permissios, please visit our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/api_keys.html#-API-Key-Permissions) or [Classroom](https://sendgrid.com/docs/Classroom/Basics/API/api_key_permissions.html).

*Tags:* `API Key Permissions`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve access requests

> This endpoint allows you to retrieve a list of all recent access requests.<br/>
> <br/>
> **Note:** The Response Header's 'link' parameter will include pagination info. For example:<br/>
> <br/>
> link: ```<https://api.sendgrid.com/v3/scopes/requests?limit=10&offset=0>; rel="first"; title="1", <https://api.sendgrid.com/v3/scopes/requests?limit=10&offset=10>; rel="last"; title="2", <https://api.sendgrid.com/v3/scopes/requests?limit=10&offset=0>; rel="prev"; title="1"```

*Tags:* `Teammates`

#### Input Parameters
* `limit` - _optional_ - Optional field to limit the number of results returned.
* `offset` - _optional_ - Optional beginning point in the list to retrieve from.

### Deny access request

> This endpoint allows you to deny an attempt to access your account.<br/>
> <br/>
> **Note:** Only teammate admins may delete a teammate's access request.

*Tags:* `Teammates`

#### Input Parameters
* `request_id` - _required_ - The ID of the request that you want to deny.

### Approve access request

> This endpoint allows you to approve an access attempt.<br/>
> <br/>
> **Note:** Only teammate admins may approve another teammate's access request.

*Tags:* `Teammates`

#### Input Parameters
* `request_id` - _required_ - The ID of the request that you want to approve.

### Get all Sender Identities

> **This endpoint allows you to retrieve a list of all sender identities that have been created for your account.**<br/>
> <br/>
> Sender Identities are required to be verified before use. If your domain has been whitelabeled it will auto verify on creation. Otherwise an email will be sent to the `from.email`.

*Tags:* `Sender Identities API`

#### Input Parameters
* `on-behalf-of` - _optional_

### Create a Sender Identity

> **This endpoint allows you to create a new sender identity.**<br/>
> <br/>
> *You may create up to 100 unique sender identities.*<br/>
> <br/>
> Sender Identities are required to be verified before use. If your domain has been whitelabeled it will auto verify on creation. Otherwise an email will be sent to the `from.email`.

*Tags:* `Sender Identities API`

#### Input Parameters
* `on-behalf-of` - _optional_

### Delete a Sender Identity

> **This endoint allows you to delete one of your sender identities.**<br/>
> <br/>
> Sender Identities are required to be verified before use. If your domain has been whitelabeled it will auto verify on creation. Otherwise an email will be sent to the `from.email`.

*Tags:* `Sender Identities API`

#### Input Parameters
* `on-behalf-of` - _optional_

### View a Sender Identity

> **This endpoint allows you to retrieve a specific sender identity.**<br/>
> <br/>
> Sender Identities are required to be verified before use. If your domain has been whitelabeled it will auto verify on creation. Otherwise an email will be sent to the `from.email`.

*Tags:* `Sender Identities API`

#### Input Parameters
* `on-behalf-of` - _optional_

### Update a Sender Identity

> **This endpoint allows you to update a sender identity.**<br/>
> <br/>
> Updates to `from.email` require re-verification. If your domain has been whitelabeled it will auto verify on creation. Otherwise an email will be sent to the `from.email`.<br/>
> <br/>
> Partial updates are allowed, but fields that are marked as "required" in the POST (create) endpoint must not be nil if that field is included in the PATCH request.

*Tags:* `Sender Identities API`

#### Input Parameters
* `on-behalf-of` - _optional_

### Resend Sender Identity Verification

> **This enpdoint allows you to resend a sender identity verification email.**<br/>
> <br/>
> Sender Identities are required to be verified before use. If your domain has been whitelabeled it will auto verify on creation. Otherwise an email will be sent to the `from.email`.

*Tags:* `Sender Identities API`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve global email statistics

> **This endpoint allows you to retrieve all of your global email statistics between a given date range.**<br/>
> <br/>
> Parent accounts will see aggregated stats for their account and all subuser accounts. Subuser accounts will only see their own stats.

*Tags:* `Stats`

#### Input Parameters
* `limit` - _optional_ - The number of results to return.
* `offset` - _optional_ - The point in the list to begin retrieving results.
* `aggregated_by` - _optional_ - How to group the statistics. Must be either "day", "week", or "month".
    Possible values: day, week, month.
* `start_date` - _required_ - The starting date of the statistics to retrieve. Must follow format YYYY-MM-DD.
* `end_date` - _optional_ - The end date of the statistics to retrieve. Defaults to today. Must follow format YYYY-MM-DD.
* `on-behalf-of` - _optional_

### List all Subusers

> This endpoint allows you to retrieve a list of all of your subusers. You can choose to retrieve specific subusers as well as limit the results that come back from the API.<br/>
> <br/>
> For more information about Subusers:<br/>
> <br/>
> * [User Guide > Subusers](https://sendgrid.com/docs/User_Guide/Settings/Subusers/index.html)<br/>
> * [Classroom > How do I add more subusers to my account?](https://sendgrid.com/docs/Classroom/Basics/Account/how_do_i_add_more_subusers_to_my_account.html)

*Tags:* `Subusers API`

#### Input Parameters
* `username` - _optional_ - The username of this subuser.
* `limit` - _optional_ - The number of results you would like to get in each request.
* `offset` - _optional_ - The number of subusers to skip.

### Create Subuser

> This endpoint allows you to retrieve a list of all of your subusers. You can choose to retrieve specific subusers as well as limit the results that come back from the API.<br/>
> <br/>
> For more information about Subusers:<br/>
> <br/>
> * [User Guide > Subusers](https://sendgrid.com/docs/User_Guide/Settings/Subusers/index.html)<br/>
> * [Classroom > How do I add more subusers to my account?](https://sendgrid.com/docs/Classroom/Basics/Account/how_do_i_add_more_subusers_to_my_account.html)

*Tags:* `Subusers API`

### Retrieve Subuser Reputations

> Subuser sender reputations give a good idea how well a sender is doing with regards to how recipients and recipient servers react to the mail that is being received. When a bounce, spam report, or other negative action happens on a sent email, it will effect your sender rating.<br/>
> <br/>
> This endpoint allows you to request the reputations for your subusers.

*Tags:* `Subusers API`

#### Input Parameters
* `usernames` - _optional_

### Retrieve email statistics for your subusers.

> **This endpoint allows you to retrieve the email statistics for the given subusers.**<br/>
> <br/>
> You may retrieve statistics for up to 10 different subusers by including an additional _subusers_ parameter for each additional subuser.<br/>
> <br/>
> While you can always view the statistics for all email activity on your account, subuser statistics enable you to view specific segments of your stats. Emails sent, bounces, and spam reports are always tracked for subusers. Unsubscribes, clicks, and opens are tracked if you have enabled the required settings.<br/>
> <br/>
> For more information, see our [User Guide](https://sendgrid.com/docs/User_Guide/Statistics/subuser.html).

*Tags:* `Subusers API`

#### Input Parameters
* `limit` - _optional_ - Limits the number of results returned per page.
* `offset` - _optional_ - The point in the list to begin retrieving results from.
* `aggregated_by` - _optional_ - How to group the statistics. Must be either "day", "week", or "month".
    Possible values: day, week, month.
* `subusers` - _required_ - The subuser you want to retrieve statistics for. You may include this parameter up to 10 times to retrieve statistics for multiple subusers.
* `start_date` - _required_ - The starting date of the statistics to retrieve. Must follow format YYYY-MM-DD.
* `end_date` - _optional_ - The end date of the statistics to retrieve. Defaults to today.

### Retrieve monthly stats for all subusers

> **This endpoint allows you to retrieve the monthly email statistics for all subusers over the given date range.**<br/>
> <br/>
> While you can always view the statistics for all email activity on your account, subuser statistics enable you to view specific segments of your stats for your subusers. Emails sent, bounces, and spam reports are always tracked for subusers. Unsubscribes, clicks, and opens are tracked if you have enabled the required settings.<br/>
> <br/>
> When using the `sort_by_metric` to sort your stats by a specific metric, you can not sort by the following metrics:<br/>
> `bounce_drops`, `deferred`, `invalid_emails`, `processed`, `spam_report_drops`, `spam_reports`, or `unsubscribe_drops`.<br/>
> <br/>
> For more information, see our [User Guide](https://sendgrid.com/docs/User_Guide/Statistics/subuser.html).

*Tags:* `Subusers API`

#### Input Parameters
* `date` - _required_ - The date of the month to retrieve statistics for. Must be formatted YYYY-MM-DD
* `subuser` - _optional_ - A substring search of your subusers.
* `sort_by_metric` - _optional_ - The metric that you want to sort by. Metrics that you can sort by are: `blocks`, `bounces`, `clicks`, `delivered`, `opens`, `requests`, `unique_clicks`, `unique_opens`, and `unsubscribes`.'
* `sort_by_direction` - _optional_ - The direction you want to sort.
    Possible values: desc, asc.
* `limit` - _optional_ - Optional field to limit the number of results returned.
* `offset` - _optional_ - Optional beginning point in the list to retrieve from.

### Retrieve the totals for each email statistic metric for all subusers.

> **This endpoint allows you to retrieve the total sums of each email statistic metric for all subusers over the given date range.**<br/>
> <br/>
> <br/>
> While you can always view the statistics for all email activity on your account, subuser statistics enable you to view specific segments of your stats. Emails sent, bounces, and spam reports are always tracked for subusers. Unsubscribes, clicks, and opens are tracked if you have enabled the required settings.<br/>
> <br/>
> For more information, see our [User Guide](https://sendgrid.com/docs/User_Guide/Statistics/subuser.html).

*Tags:* `Subusers API`

#### Input Parameters
* `sort_by_direction` - _optional_ - The direction you want to sort. 
    Possible values: desc, asc.
* `start_date` - _required_ - The starting date of the statistics to retrieve. Must follow format YYYY-MM-DD.
* `end_date` - _optional_ - The end date of the statistics to retrieve. Defaults to today. Must follow format YYYY-MM-DD.
* `limit` - _optional_ - Limits the number of results returned per page.
* `offset` - _optional_ - The point in the list to begin retrieving results from.
* `aggregated_by` - _optional_ - How to group the statistics. Defaults to today. Must follow format YYYY-MM-DD.
* `sort_by_metric` - _optional_ - The metric that you want to sort by.  Must be a single metric.

### Delete a subuser

> This endpoint allows you to delete a subuser. This is a permanent action, once deleted a subuser cannot be retrieved.<br/>
> <br/>
> For more information about Subusers:<br/>
> <br/>
> * [User Guide > Subusers](https://sendgrid.com/docs/User_Guide/Settings/Subusers/index.html)<br/>
> * [Classroom > How do I add more subusers to my account?](https://sendgrid.com/docs/Classroom/Basics/Account/how_do_i_add_more_subusers_to_my_account.html)

*Tags:* `Subusers API`

#### Input Parameters
* `subuser_name` - _required_

### Enable/disable a subuser

> This endpoint allows you to enable or disable a subuser.<br/>
> <br/>
> For more information about Subusers:<br/>
> <br/>
> * [User Guide > Subusers](https://sendgrid.com/docs/User_Guide/Settings/Subusers/index.html)<br/>
> * [Classroom > How do I add more subusers to my account?](https://sendgrid.com/docs/Classroom/Basics/Account/how_do_i_add_more_subusers_to_my_account.html)

*Tags:* `Subusers API`

#### Input Parameters
* `subuser_name` - _required_

### Update IPs assigned to a subuser

> Each subuser should be assigned to an IP address, from which all of this subuser's mail will be sent. Often, this is the same IP as the parent account, but each subuser can have their own, or multiple, IP addresses as well. <br/>
> <br/>
> More information:<br/>
> <br/>
> * [How to request more IPs](https://sendgrid.com/docs/Classroom/Basics/Account/adding_an_additional_dedicated_ip_to_your_account.html)<br/>
> * [IPs can be whitelabeled](https://sendgrid.com/docs/User_Guide/Settings/Whitelabel/ips.html)

*Tags:* `Subusers API`

#### Input Parameters
* `Authorization` - _required_

### Delete monitor settings

> Subuser monitor settings allow you to receive a sample of an outgoing message by a specific customer at a specific frequency of emails.

*Tags:* `Subusers API`

#### Input Parameters
* `Authorization` - _required_

### Retrieve monitor settings for a subuser

> Subuser monitor settings allow you to receive a sample of an outgoing message by a specific customer at a specific frequency of emails.

*Tags:* `Subusers API`

#### Input Parameters
* `subuser_name` - _required_ - The name of the subuser for which to retrieve monitor settings.

### Create monitor settings

> Subuser monitor settings allow you to receive a sample of an outgoing message by a specific customer at a specific frequency of emails.

*Tags:* `Subusers API`

#### Input Parameters
* `subuser_name` - _required_ - The name of the subuser for which to retrieve monitor settings.

### Update Monitor Settings for a subuser

> Subuser monitor settings allow you to receive a sample of an outgoing message by a specific customer at a specific frequency of emails.

*Tags:* `Subusers API`

#### Input Parameters
* `subuser_name` - _required_ - The name of the subuser for which to retrieve monitor settings.

### Retrieve the monthly email statistics for a single subuser

> **This endpoint allows you to retrive the monthly email statistics for a specific subuser.**<br/>
> <br/>
> While you can always view the statistics for all email activity on your account, subuser statistics enable you to view specific segments of your stats for your subusers. Emails sent, bounces, and spam reports are always tracked for subusers. Unsubscribes, clicks, and opens are tracked if you have enabled the required settings.<br/>
> <br/>
> When using the `sort_by_metric` to sort your stats by a specific metric, you can not sort by the following metrics:<br/>
> `bounce_drops`, `deferred`, `invalid_emails`, `processed`, `spam_report_drops`, `spam_reports`, or `unsubscribe_drops`.<br/>
> <br/>
> For more information, see our [User Guide](https://sendgrid.com/docs/User_Guide/Statistics/subuser.html).

*Tags:* `Subusers API`

#### Input Parameters
* `date` - _required_ - The date of the month to retrieve statistics for. Must be formatted YYYY-MM-DD
* `sort_by_metric` - _optional_ - The metric that you want to sort by. Metrics that you can sort by are: `blocks`, `bounces`, `clicks`, `delivered`, `opens`, `requests`, `unique_clicks`, `unique_opens`, and `unsubscribes`.'
* `sort_by_direction` - _optional_ - The direction you want to sort.
    Possible values: desc, asc.
* `limit` - _optional_ - Optional field to limit the number of results returned.
* `offset` - _optional_ - Optional beginning point in the list to retrieve from.

### Delete blocks

> **This endpoint allows you to delete all email addresses on your blocks list.**<br/>
> <br/>
> There are two options for deleting blocked emails: <br/>
> <br/>
> 1. You can delete all blocked emails by setting `delete_all` to true in the request body. <br/>
> 2. You can delete some blocked emails by specifying the email addresses in an array in the request body.<br/>
> <br/>
> [Blocks](https://sendgrid.com/docs/Glossary/blocks.html) happen when your message was rejected for a reason related to the message, not the recipient address. This can happen when your mail server IP address has been added to a blacklist or blocked by an ISP, or if the message content is flagged by a filter on the receiving server.<br/>
> <br/>
> For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/blocks.html).

*Tags:* `Blocks API`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve all blocks

> **This endpoint allows you to retrieve a list of all email addresses that are currently on your blocks list.**<br/>
> <br/>
> There are several causes for [blocked](https://sendgrid.com/docs/Glossary/blocks.html) emails: for example, your mail server IP address is on an ISP blacklist, or blocked by an ISP, or if the receiving server flags the message content.<br/>
> <br/>
> For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/blocks.html).

*Tags:* `Blocks API`

#### Input Parameters
* `start_time` - _optional_ - Refers start of the time range in unix timestamp when a blocked email was created (inclusive).
* `end_time` - _optional_ - Refers end of the time range in unix timestamp when a blocked email was created (inclusive).
* `limit` - _optional_ - Limit the number of results to be displayed per page.
* `offset` - _optional_ - The point in the list to begin displaying results.
* `on-behalf-of` - _optional_

### Delete a specific block

> **This endpoint allows you to delete a specific email address from your blocks list.**<br/>
> <br/>
> [Blocks](https://sendgrid.com/docs/Glossary/blocks.html) happen when your message was rejected for a reason related to the message, not the recipient address. This can happen when your mail server IP address has been added to a blacklist or blocked by an ISP, or if the message content is flagged by a filter on the receiving server.<br/>
> <br/>
> For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/blocks.html).

*Tags:* `Blocks API`

#### Input Parameters
* `Authorization` - _required_
* `on-behalf-of` - _optional_

### Retrieve a specific block

> **This endpoint allows you to retrieve a specific email address from your blocks list.**<br/>
> <br/>
> [Blocks](https://sendgrid.com/docs/Glossary/blocks.html) happen when your message was rejected for a reason related to the message, not the recipient address. This can happen when your mail server IP address has been added to a blacklist or blocked by an ISP, or if the message content is flagged by a filter on the receiving server.<br/>
> <br/>
> For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/blocks.html).

*Tags:* `Blocks API`

#### Input Parameters
* `on-behalf-of` - _optional_

### Delete bounces

> **This endpoint allows you to delete all of your bounces. You can also use this endpoint to remove a specific email address from your bounce list.**<br/>
> <br/>
> A bounced email is when the message is undeliverable and then returned to the server that sent it.<br/>
> <br/>
> For more information see: <br/>
> <br/>
> * [User Guide > Bounces](https://sendgrid.com/docs/User_Guide/Suppressions/bounces.html) for more information<br/>
> * [Glossary > Bounces](https://sendgrid.com/docs/Glossary/Bounces.html)<br/>
> * [Classroom > List Scrubbing Guide](https://sendgrid.com/docs/Classroom/Deliver/list_scrubbing.html)<br/>
> <br/>
> Note: the `delete_all` and `emails` parameters should be used independently of each other as they have different purposes.

*Tags:* `Bounces API`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve all bounces

> **This endpoint allows you to retrieve all of your bounces.**<br/>
> <br/>
> A bounced email is when the message is undeliverable and then returned to the server that sent it.  <br/>
> <br/>
> For more information see: <br/>
> <br/>
> * [User Guide > Bounces](https://sendgrid.com/docs/User_Guide/Suppressions/bounces.html) for more information<br/>
> * [Glossary > Bounces](https://sendgrid.com/docs/Glossary/Bounces.html)

*Tags:* `Bounces API`

#### Input Parameters
* `start_time` - _optional_ - Refers start of the time range in unix timestamp when a bounce was created (inclusive).
* `end_time` - _optional_ - Refers end of the time range in unix timestamp when a bounce was created (inclusive).
* `Accept` - _required_
* `on-behalf-of` - _optional_

### Delete a bounce

> **This endpoint allows you to remove an email address from your bounce list.**<br/>
> <br/>
> A bounced email is when the message is undeliverable and then returned to the server that sent it. This endpoint allows you to delete a single email addresses from your bounce list. <br/>
> <br/>
> For more information see: <br/>
> <br/>
> * [User Guide > Bounces](https://sendgrid.com/docs/User_Guide/Suppressions/bounces.html) for more information<br/>
> * [Glossary > Bounces](https://sendgrid.com/docs/Glossary/Bounces.html)<br/>
> * [Classroom > List Scrubbing Guide](https://sendgrid.com/docs/Classroom/Deliver/list_scrubbing.html)

*Tags:* `Bounces API`

#### Input Parameters
* `email_address` - _required_ - The email address you would like to remove from the bounce list.
* `on-behalf-of` - _optional_

### Retrieve a Bounce

> **This endpoint allows you to retrieve a specific bounce for a given email address.**<br/>
> <br/>
> A bounced email is when the message is undeliverable and then returned to the server that sent it.<br/>
> <br/>
> For more information see: <br/>
> <br/>
> * [User Guide > Bounces](https://sendgrid.com/docs/User_Guide/Suppressions/bounces.html) for more information<br/>
> * [Glossary > Bounces](https://sendgrid.com/docs/Glossary/Bounces.html)<br/>
> * [Classroom > List Scrubbing Guide](https://sendgrid.com/docs/Classroom/Deliver/list_scrubbing.html)

*Tags:* `Bounces API`

#### Input Parameters
* `on-behalf-of` - _optional_

### Delete invalid emails

> **This endpoint allows you to remove email addresses from your invalid email address list.**<br/>
> <br/>
> There are two options for deleting invalid email addresses: <br/>
> <br/>
> 1) You can delete all invalid email addresses by setting `delete_all` to true in the request body.<br/>
> 2) You can delete some invalid email addresses by specifying certain addresses in an array in the request body.<br/>
> <br/>
> An invalid email occurs when you attempt to send email to an address that is formatted in a manner that does not meet internet email format standards or the email does not exist at the recipient's mail server.<br/>
> <br/>
> Examples include addresses without the "@" sign or addresses that include certain special characters and/or spaces. This response can come from our own server or the recipient mail server.<br/>
> <br/>
> For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/invalid_emails.html).

*Tags:* `Invalid Emails API`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve all invalid emails

> **This endpoint allows you to retrieve a list of all invalid email addresses.**<br/>
> <br/>
> An invalid email occurs when you attempt to send email to an address that is formatted in a manner that does not meet internet email format standards or the email does not exist at the recipient's mail server.<br/>
> <br/>
> Examples include addresses without the "@" sign or addresses that include certain special characters and/or spaces. This response can come from our own server or the recipient mail server.<br/>
> <br/>
> For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/invalid_emails.html).

*Tags:* `Invalid Emails API`

#### Input Parameters
* `start_time` - _optional_ - Refers start of the time range in unix timestamp when an invalid email was created (inclusive).
* `end_time` - _optional_ - Refers end of the time range in unix timestamp when an invalid email was created (inclusive).
* `limit` - _optional_ - Limit the number of results to be displayed per page.
* `offset` - _optional_ - Paging offset. The point in the list to begin displaying results.
* `on-behalf-of` - _optional_

### Delete a specific invalid email

> **This endpoint allows you to remove a specific email address from the invalid email address list.**<br/>
> <br/>
> An invalid email occurs when you attempt to send email to an address that is formatted in a manner that does not meet internet email format standards or the email does not exist at the recipient's mail server.<br/>
> <br/>
> Examples include addresses without the "@" sign or addresses that include certain special characters and/or spaces. This response can come from our own server or the recipient mail server.<br/>
> <br/>
> For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/invalid_emails.html).

*Tags:* `Invalid Emails API`

#### Input Parameters
* `Authorization` - _required_
* `on-behalf-of` - _optional_

### Retrieve a specific invalid email

> **This endpoint allows you to retrieve a specific invalid email addresses.**<br/>
> <br/>
> An invalid email occurs when you attempt to send email to an address that is formatted in a manner that does not meet internet email format standards or the email does not exist at the recipient's mail server.<br/>
> <br/>
> Examples include addresses without the "@" sign or addresses that include certain special characters and/or spaces. This response can come from our own server or the recipient mail server.<br/>
> <br/>
> For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/invalid_emails.html).

*Tags:* `Invalid Emails API`

#### Input Parameters
* `Authorization` - _required_
* `on-behalf-of` - _optional_

### Delete spam reports

> **This endpoint allows you to delete your spam reports.**<br/>
> <br/>
> There are two options for deleting spam reports: <br/>
> <br/>
> 1) You can delete all spam reports by setting "delete_all" to true in the request body. <br/>
> 2) You can delete some spam reports by specifying the email addresses in an array in the request body.<br/>
> <br/>
> [Spam reports](https://sendgrid.com/docs/Glossary/spam_reports.html) happen when a recipient indicates that they think your email is [spam](https://sendgrid.com/docs/Glossary/spam.html) and then their email provider reports this to SendGrid.<br/>
> <br/>
> For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/spam_reports.html).

*Tags:* `Spam Reports API`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve all spam reports

> **This endpoint allows you to retrieve all spam reports.**<br/>
> <br/>
> [Spam reports](https://sendgrid.com/docs/Glossary/spam_reports.html) happen when a recipient indicates that they think your email is [spam](https://sendgrid.com/docs/Glossary/spam.html) and then their email provider reports this to SendGrid.<br/>
> <br/>
> For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/spam_reports.html).

*Tags:* `Spam Reports API`

#### Input Parameters
* `start_time` - _optional_ - Refers start of the time range in unix timestamp when a spam report was created (inclusive).
* `end_time` - _optional_ - Refers end of the time range in unix timestamp when a spam report was created (inclusive).
* `limit` - _optional_ - Limit the number of results to be displayed per page.
* `offset` - _optional_ - Paging offset. The point in the list to begin displaying results.
* `on-behalf-of` - _optional_

### Delete a specific spam report

> **This endpoint allows you to delete a specific spam report.**<br/>
> <br/>
> [Spam reports](https://sendgrid.com/docs/Glossary/spam_reports.html) happen when a recipient indicates that they think your email is [spam](https://sendgrid.com/docs/Glossary/spam.html) and then their email provider reports this to SendGrid.<br/>
> <br/>
> For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/spam_reports.html).

*Tags:* `Spam Reports API`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve a specific spam report

> **This endpoint allows you to retrieve a specific spam report.**<br/>
> <br/>
> [Spam reports](https://sendgrid.com/docs/Glossary/spam_reports.html) happen when a recipient indicates that they think your email is [spam](https://sendgrid.com/docs/Glossary/spam.html) and then their email provider reports this to SendGrid.<br/>
> <br/>
> For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/spam_reports.html).

*Tags:* `Spam Reports API`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve all global suppressions

> **This endpoint allows you to retrieve a list of all email address that are globally suppressed.**<br/>
> <br/>
> A global suppression (or global unsubscribe) is an email address of a recipient who does not want to receive any of your messages. A globally suppressed recipient will be removed from any email you send. For more information, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Suppressions/global_unsubscribes.html).

*Tags:* `Suppressions - Global Suppressions`

#### Input Parameters
* `start_time` - _optional_ - Refers start of the time range in unix timestamp when an unsubscribe email was created (inclusive).
* `end_time` - _optional_ - Refers end of the time range in unix timestamp when an unsubscribe email was created (inclusive).
* `limit` - _optional_ - The number of results to display on each page.
* `offset` - _optional_ - The point in the list of results to begin displaying global suppressions.
* `on-behalf-of` - _optional_

### Retrieve all teammates

> This endpoint allows you to retrieve a list of all current teammates.<br/>
> <br/>
> **Note:** The Response Header will include pagination info. For example:<br/>
> <br/>
> link: ```<https://api.sendgrid.com/v3/teammates?limit=10&offset=0>; rel="first"; title="1", <https://api.sendgrid.com/v3/teammates?limit=10&offset=10>; rel="last"; title="2", <https://api.sendgrid.com/v3/teammates?limit=10&offset=0>; rel="prev"; title="1"```

*Tags:* `Teammates`

#### Input Parameters
* `limit` - _optional_ - Number of items to return
* `offset` - _optional_ - Paging offset

### Invite teammate

> This endpoint allows you to send a teammate invitation via email with a predefined set of scopes, or permissions.<br/>
> <br/>
> **Note:** A teammate invite will expire after 7 days, but you may resend the invite at any time to reset the expiration date.<br/>
> <br/>
> Essentials, [Legacy Lite](https://sendgrid.com/docs/Classroom/Basics/Billing/legacy_lite_plan.html), and Free Trial users may create up to one teammate per account. There are no limits for how many teammates a Pro or higher account may create.

*Tags:* `Teammates`

### Retrieve all pending teammates

> This endpoint allows you to retrieve a list of all pending teammate invitations.<br/>
> <br/>
> **Note:** Each teammate invitation is valid for 7 days. Users may resend the invite to refresh the expiration date.

*Tags:* `Teammates`

### Delete pending teammate

> This endpoint allows you to delete a pending teammate invite.

*Tags:* `Teammates`

#### Input Parameters
* `token` - _required_ - The token for the invite you want to delete.

### Resend teammate invite

> This endpoint allows you to resend a teammate invite.<br/>
> <br/>
> **Note:** Teammate invitations will expire after 7 days. Resending an invite will reset the expiration date.

*Tags:* `Teammates`

#### Input Parameters
* `token` - _required_ - The token for the invite that you want to resend.

### Delete teammate

> This endpoint allows you to delete a teammate.<br/>
> <br/>
> **Only the parent user or an admin teammate can delete another teammate.**

*Tags:* `Teammates`

#### Input Parameters
* `username` - _required_ - The username of the teammate that you want to retrieve.

### Retrieve specific teammate

> This endpoint allows you to retrieve a specific teammate by username.

*Tags:* `Teammates`

#### Input Parameters
* `username` - _required_ - The username of the teammate that you want to retrieve.

### Update teammate's permissions

> This endpoint allows you to update a teammate's permissions.<br/>
> <br/>
> To turn a teammate into an admin, the request body should contain an `is_admin` set to `true`. Otherwise, set `is_admin` to `false` and pass in all the scopes that a teammate should have.<br/>
> <br/>
> **Only the parent user or other admin teammates can update another teammate's permissions.**<br/>
> <br/>
> **Admin users can only update permissions.**

*Tags:* `Teammates`

#### Input Parameters
* `username` - _required_ - The username of the teammate that you want to retrieve.

### Retrieve all transactional templates.

> **This endpoint allows you to retrieve all transactional templates.**<br/>
> <br/>
> Each user can create up to 300 different transactional templates. Transactional templates are specific to accounts and subusers. Templates created on a parent account will not be accessible from the subuser accounts.<br/>
> <br/>
> Transactional templates are templates created specifically for transactional email and are not to be confused with [Marketing Campaigns templates](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/templates.html). For more information about transactional templates, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Transactional_Templates/index.html).

*Tags:* `Transactional Templates`

#### Input Parameters
* `on-behalf-of` - _optional_

### Create a transactional template.

> **This endpoint allows you to create a transactional template.**<br/>
> <br/>
> Each user can create up to 300 different transactional templates. Transactional templates are specific to accounts and subusers. Templates created on a parent account will not be accessible from the subuser accounts.<br/>
> <br/>
> Transactional templates are templates created specifically for transactional email and are not to be confused with [Marketing Campaigns templates](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/templates.html). For more information about transactional templates, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Transactional_Templates/index.html).

*Tags:* `Transactional Templates`

#### Input Parameters
* `on-behalf-of` - _optional_

### Delete a template.

> **This endpoint allows you to delete a transactional template.**<br/>
> <br/>
> Each user can create up to 300 different transactional templates. Transactional templates are specific to accounts and subusers. Templates created on a parent account will not be accessible from the subuser accounts.<br/>
> <br/>
> Transactional templates are templates created specifically for transactional email and are not to be confused with [Marketing Campaigns templates](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/templates.html). For more information about transactional templates, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Transactional_Templates/index.html).

*Tags:* `Transactional Templates`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve a single transactional template.

> **This endpoint allows you to retrieve a single transactional template.**<br/>
> <br/>
> Each user can create up to 300 different transactional templates. Transactional templates are specific to accounts and subusers. Templates created on a parent account will not be accessible from the subuser accounts.<br/>
> <br/>
> Transactional templates are templates created specifically for transactional email and are not to be confused with [Marketing Campaigns templates](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/templates.html). For more information about transactional templates, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Transactional_Templates/index.html).

*Tags:* `Transactional Templates`

#### Input Parameters
* `on-behalf-of` - _optional_

### Edit a transactional template.

> **This endpoint allows you to edit a transactional template.**<br/>
> <br/>
> Each user can create up to 300 different transactional templates. Transactional templates are specific to accounts and subusers. Templates created on a parent account will not be accessible from the subuser accounts.<br/>
> <br/>
> Transactional templates are templates created specifically for transactional email and are not to be confused with [Marketing Campaigns templates](https://sendgrid.com/docs/User_Guide/Marketing_Campaigns/templates.html). For more information about transactional templates, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Transactional_Templates/index.html).

*Tags:* `Transactional Templates`

#### Input Parameters
* `on-behalf-of` - _optional_

### Create a new transactional template version.

> **This endpoint allows you to create a new version of a template.**<br/>
> <br/>
> Each transactional template can have multiple versions, each version with its own subject and content. Each user can have up to 300 versions across across all templates.<br/>
> <br/>
> For more information about transactional templates, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Transactional_Templates/index.html).

*Tags:* `Transactional Templates Versions`

#### Input Parameters
* `on-behalf-of` - _optional_

### Delete a transactional template version.

> **This endpoint allows you to delete one of your transactional template versions.**<br/>
> <br/>
> Each transactional template can have multiple versions, each version with its own subject and content. Each user can have up to 300 versions across across all templates.<br/>
> <br/>
> For more information about transactional templates, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Transactional_Templates/index.html).<br/>
> <br/>
> ## URI Parameters<br/>
> | URI Parameter | Type | Description |<br/>
> |---|---|---|<br/>
> | template_id | string | The ID of the original template |<br/>
> | version_id | string | The ID of the template version |

*Tags:* `Transactional Templates Versions`

#### Input Parameters
* `on-behalf-of` - _optional_
* `version_id` - _required_

### Retrieve a specific transactional template version.

> **This endpoint allows you to retrieve a specific version of a template.**<br/>
> <br/>
> Each transactional template can have multiple versions, each version with its own subject and content. Each user can have up to 300 versions across across all templates.<br/>
> <br/>
> For more information about transactional templates, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Transactional_Templates/index.html).<br/>
> <br/>
> ## URI Parameters<br/>
> | URI Parameter | Type | Description |<br/>
> |---|---|---|<br/>
> | template_id | string | The ID of the original template |<br/>
> | version_id | string |  The ID of the template version |

*Tags:* `Transactional Templates Versions`

#### Input Parameters
* `on-behalf-of` - _optional_
* `version_id` - _required_

### Edit a transactional template version.

> **This endpoint allows you to edit a version of one of your transactional templates.**<br/>
> <br/>
> Each transactional template can have multiple versions, each version with its own subject and content. Each user can have up to 300 versions across across all templates.<br/>
> <br/>
> For more information about transactional templates, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Transactional_Templates/index.html).<br/>
> <br/>
> ## URI Parameters<br/>
> | URI Parameter | Type | Description |<br/>
> |---|---|---|<br/>
> | template_id | string | The ID of the original template |<br/>
> | version_id | string | The ID of the template version |

*Tags:* `Transactional Templates Versions`

#### Input Parameters
* `on-behalf-of` - _optional_
* `version_id` - _required_

### Activate a transactional template version.

> **This endpoint allows you to activate a version of one of your templates.**<br/>
> <br/>
> Each transactional template can have multiple versions, each version with its own subject and content. Each user can have up to 300 versions across across all templates.<br/>
> <br/>
> <br/>
> For more information about transactional templates, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Transactional_Templates/index.html).<br/>
> <br/>
> ## URI Parameters<br/>
> | URI Parameter | Type | Description |<br/>
> |---|---|---|<br/>
> | template_id | string | The ID of the original template |<br/>
> | version_id | string |  The ID of the template version |

*Tags:* `Transactional Templates Versions`

#### Input Parameters
* `on-behalf-of` - _optional_
* `version_id` - _required_

### Retrieve Tracking Settings

> **This endpoint allows you to retrieve a list of all tracking settings that you can enable on your account.**<br/>
> <br/>
> You can track a variety of the actions your recipients may take when interacting with your emails including opening your emails, clicking on links in your emails, and subscribing to (or unsubscribing from) your emails.<br/>
> <br/>
> For more information about tracking, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html).

*Tags:* `Settings - Tracking`

#### Input Parameters
* `limit` - _optional_ - The number of settings to return.
* `offset` - _optional_ - Where in the list of results you want to begin retrieving settings.
* `on-behalf-of` - _optional_

### Retrieve Click Track Settings

> **This endpoint allows you to retrieve your current click tracking setting.**<br/>
> <br/>
> You can track a variety of the actions your recipients may take when interacting with your emails including opening your emails, clicking on links in your emails, and subscribing to (or unsubscribing from) your emails.<br/>
> <br/>
> For more information about tracking, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html).

*Tags:* `Settings - Tracking`

#### Input Parameters
* `on-behalf-of` - _optional_

### Update Click Tracking Settings

> **This endpoint allows you to change your current click tracking setting. You can enable, or disable, click tracking using this endpoint.**<br/>
> <br/>
> You can track a variety of the actions your recipients may take when interacting with your emails including opening your emails, clicking on links in your emails, and subscribing to (or unsubscribing from) your emails.<br/>
> <br/>
> For more information about tracking, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html).

*Tags:* `Settings - Tracking`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve Google Analytics Settings

> **This endpoint allows you to retrieve your current setting for Google Analytics.**<br/>
> <br/>
> For more information about using Google Analytics, please refer to [Google's URL Builder](https://support.google.com/analytics/answer/1033867?hl=en) and their article on ["Best Practices for Campaign Building"](https://support.google.com/analytics/answer/1037445).<br/>
> <br/>
> We default the settings to Google's recommendations. For more information, see [Google Analytics Demystified](https://sendgrid.com/docs/Classroom/Track/Collecting_Data/google_analytics_demystified_ga_statistics_vs_sg_statistics.html).<br/>
> <br/>
> You can track a variety of the actions your recipients may take when interacting with your emails including opening your emails, clicking on links in your emails, and subscribing to (or unsubscribing from) your emails.<br/>
> <br/>
> For more information about tracking, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html).

*Tags:* `Settings - Tracking`

#### Input Parameters
* `on-behalf-of` - _optional_

### Update Google Analytics Settings

> **This endpoint allows you to update your current setting for Google Analytics.**<br/>
> <br/>
> For more information about using Google Analytics, please refer to [Google's URL Builder](https://support.google.com/analytics/answer/1033867?hl=en) and their article on ["Best Practices for Campaign Building"](https://support.google.com/analytics/answer/1037445).<br/>
> <br/>
> We default the settings to Google's recommendations. For more information, see [Google Analytics Demystified](https://sendgrid.com/docs/Classroom/Track/Collecting_Data/google_analytics_demystified_ga_statistics_vs_sg_statistics.html).<br/>
> <br/>
> You can track a variety of the actions your recipients may take when interacting with your emails including opening your emails, clicking on links in your emails, and subscribing to (or unsubscribing from) your emails.<br/>
> <br/>
> For more information about tracking, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html).

*Tags:* `Settings - Tracking`

#### Input Parameters
* `on-behalf-of` - _optional_

### Get Open Tracking Settings

> **This endpoint allows you to retrieve your current settings for open tracking.**<br/>
> <br/>
> Open Tracking adds an invisible image at the end of the email which can track email opens. If the email recipient has images enabled on their email client, a request to SendGrid's server for the invisible image is executed and an open event is logged. These events are logged in the Statistics portal, Email Activity interface, and are reported by the Event Webhook.<br/>
> <br/>
> You can track a variety of the actions your recipients may take when interacting with your emails including opening your emails, clicking on links in your emails, and subscribing to (or unsubscribing from) your emails.<br/>
> <br/>
> For more information about tracking, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html).

*Tags:* `Settings - Tracking`

#### Input Parameters
* `on-behalf-of` - _optional_

### Update Open Tracking Settings

> **This endpoint allows you to update your current settings for open tracking.**<br/>
> <br/>
> Open Tracking adds an invisible image at the end of the email which can track email opens. If the email recipient has images enabled on their email client, a request to SendGrid's server for the invisible image is executed and an open event is logged. These events are logged in the Statistics portal, Email Activity interface, and are reported by the Event Webhook.<br/>
> <br/>
> You can track a variety of the actions your recipients may take when interacting with your emails including opening your emails, clicking on links in your emails, and subscribing to (or unsubscribing from) your emails.<br/>
> <br/>
> For more information about tracking, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html).

*Tags:* `Settings - Tracking`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve Subscription Tracking Settings

> **This endpoint allows you to retrieve your current settings for subscription tracking.**<br/>
> <br/>
> Subscription tracking adds links to the bottom of your emails that allows your recipients to subscribe to, or unsubscribe from, your emails.<br/>
> <br/>
> You can track a variety of the actions your recipients may take when interacting with your emails including opening your emails, clicking on links in your emails, and subscribing to (or unsubscribing from) your emails.<br/>
> <br/>
> For more information about tracking, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html).

*Tags:* `Settings - Tracking`

#### Input Parameters
* `on-behalf-of` - _optional_

### Update Subscription Tracking Settings

> **This endpoint allows you to update your current settings for subscription tracking.**<br/>
> <br/>
> Subscription tracking adds links to the bottom of your emails that allows your recipients to subscribe to, or unsubscribe from, your emails.<br/>
> <br/>
> You can track a variety of the actions your recipients may take when interacting with your emails including opening your emails, clicking on links in your emails, and subscribing to (or unsubscribing from) your emails.<br/>
> <br/>
> For more information about tracking, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/tracking.html).

*Tags:* `Settings - Tracking`

#### Input Parameters
* `on-behalf-of` - _optional_

### Get a user's account information.

> **This endpoint allows you to retrieve your user account details.**<br/>
> <br/>
> Your user's account information includes the user's account type and reputation.<br/>
> <br/>
> Keeping your user profile up to date is important. This will help SendGrid to verify who you are as well as contact you should we need to.<br/>
> <br/>
> For more information about your user profile:<br/>
> <br/>
> * [SendGrid Account Settings](https://sendgrid.com/docs/User_Guide/Settings/account.html)

*Tags:* `Users API`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve your credit balance

> **This endpoint allows you to retrieve the current credit balance for your account.**<br/>
> <br/>
> Your monthly credit allotment limits the number of emails you may send before incurring overage charges. For more information about credits and billing, please visit our [Clssroom](https://sendgrid.com/docs/Classroom/Basics/Billing/billing_info_and_faqs.html).

*Tags:* `Users API`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve your account email address

> **This endpoint allows you to retrieve the email address currently on file for your account.**<br/>
> <br/>
> Keeping your user profile up to date is important. This will help SendGrid to verify who you are as well as contact you should we need to.<br/>
> <br/>
> For more information about your user profile:<br/>
> <br/>
> * [SendGrid Account Settings](https://sendgrid.com/docs/User_Guide/Settings/account.html)

*Tags:* `Users API`

#### Input Parameters
* `on-behalf-of` - _optional_

### Update your account email address

> **This endpoint allows you to update the email address currently on file for your account.**<br/>
> <br/>
> Keeping your user profile up to date is important. This will help SendGrid to verify who you are as well as contact you should we need to.<br/>
> <br/>
> For more information about your user profile:<br/>
> <br/>
> * [SendGrid Account Settings](https://sendgrid.com/docs/User_Guide/Settings/account.html)

*Tags:* `Users API`

#### Input Parameters
* `on-behalf-of` - _optional_

### Update your password

> **This endpoint allows you to update your password.**<br/>
> <br/>
> Keeping your user profile up to date is important. This will help SendGrid to verify who you are as well as contact you should we need to.<br/>
> <br/>
> For more information about your user profile:<br/>
> <br/>
> * [SendGrid Account Settings](https://sendgrid.com/docs/User_Guide/Settings/account.html)

*Tags:* `Users API`

#### Input Parameters
* `on-behalf-of` - _optional_

### Get a user's profile

> Keeping your user profile up to date is important. This will help SendGrid to verify who you are as well as contact you should we need to.<br/>
> <br/>
> For more information about your user profile:<br/>
> <br/>
> * [SendGrid Account Settings](https://sendgrid.com/docs/User_Guide/Settings/account.html)

*Tags:* `Users API`

#### Input Parameters
* `on-behalf-of` - _optional_

### Update a user's profile

> **This endpoint allows you to update your current profile details.**<br/>
> <br/>
> Keeping your user profile up to date is important. This will help SendGrid to verify who you are as well as contact you should we need to.<br/>
> <br/>
> For more information about your user profile:<br/>
> <br/>
> * [SendGrid Account Settings](https://sendgrid.com/docs/User_Guide/Settings/account.html)<br/>
> <br/>
> It should be noted that any one or more of the parameters can be updated via the PATCH /user/profile endpoint. The only requirement is that you include at least one when you PATCH.

*Tags:* `Users API`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve all scheduled sends

> **This endpoint allows you to retrieve all cancel/paused scheduled send information.**<br/>
> <br/>
> The Cancel Scheduled Sends feature allows the customer to cancel a scheduled send based on a Batch ID included in the SMTPAPI header. Scheduled sends cancelled less than 10 minutes before the scheduled time are not guaranteed to be cancelled.

*Tags:* `Cancel Scheduled Sends`

### Cancel or pause a scheduled send

> **This endpoint allows you to cancel or pause an email that has been scheduled to be sent.**<br/>
> <br/>
> If the maximum number of cancellations/pauses are added, HTTP 400 will<br/>
> be returned.<br/>
> <br/>
> The Cancel Scheduled Sends feature allows the customer to cancel a scheduled send based on a Batch ID included in the SMTPAPI header. Scheduled sends cancelled less than 10 minutes before the scheduled time are not guaranteed to be cancelled.

*Tags:* `Cancel Scheduled Sends`

### Delete a cancellation or pause of a scheduled send

> **This endpoint allows you to delete the cancellation/pause of a scheduled send.**<br/>
> <br/>
> The Cancel Scheduled Sends feature allows the customer to cancel a scheduled send based on a Batch ID included in the SMTPAPI header. Scheduled sends cancelled less than 10 minutes before the scheduled time are not guaranteed to be cancelled.

*Tags:* `Cancel Scheduled Sends`

#### Input Parameters
* `batch_id` - _required_

### Retrieve scheduled send

> **This endpoint allows you to retrieve the cancel/paused scheduled send information for a specific `batch_id`.**<br/>
> <br/>
> The Cancel Scheduled Sends feature allows the customer to cancel a scheduled send based on a Batch ID included in the SMTPAPI header. Scheduled sends cancelled less than 10 minutes before the scheduled time are not guaranteed to be cancelled.

*Tags:* `Cancel Scheduled Sends`

#### Input Parameters
* `batch_id` - _required_

### Update user scheduled send information

> **This endpoint allows you to update the status of a scheduled send for the given `batch_id`.**<br/>
> <br/>
> The Cancel Scheduled Sends feature allows the customer to cancel a scheduled send based on a Batch ID included in the SMTPAPI header. Scheduled sends cancelled less than 10 minutes before the scheduled time are not guaranteed to be cancelled.

*Tags:* `Cancel Scheduled Sends`

#### Input Parameters
* `batch_id` - _required_

### Retrieve current Enforced TLS settings.

> **This endpoint allows you to retrieve your current Enforced TLS settings.**<br/>
> <br/>
> The Enforced TLS settings specify whether or not the recipient is required to support TLS or have a valid certificate. See the [SMTP Ports User Guide](https://sendgrid.com/docs/Classroom/Basics/Email_Infrastructure/smtp_ports.html) for more information on opportunistic TLS.<br/>
> <br/>
> **Note:** If either setting is enabled and the recipient does not support TLS or have a valid certificate, we drop the message and send a block event with "TLS required but not supported" as the description.

*Tags:* `Settings - Enforced TLS`

#### Input Parameters
* `on-behalf-of` - _optional_

### Update Enforced TLS settings

> **This endpoint allows you to update your current Enforced TLS settings.**<br/>
> <br/>
> The Enforced TLS settings specify whether or not the recipient is required to support TLS or have a valid certificate. See the [SMTP Ports User Guide](https://sendgrid.com/docs/Classroom/Basics/Email_Infrastructure/smtp_ports.html) for more information on opportunistic TLS.<br/>
> <br/>
> **Note:** If either setting is enabled and the recipient does not support TLS or have a valid certificate, we drop the message and send a block event with "TLS required but not supported" as the description.

*Tags:* `Settings - Enforced TLS`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve your username

> **This endpoint allows you to retrieve your current account username.**<br/>
> <br/>
> Keeping your user profile up to date is important. This will help SendGrid to verify who you are as well as contact you should we need to.<br/>
> <br/>
> For more information about your user profile:<br/>
> <br/>
> * [SendGrid Account Settings](https://sendgrid.com/docs/User_Guide/Settings/account.html)

*Tags:* `Users API`

#### Input Parameters
* `on-behalf-of` - _optional_

### Update your username

> **This endpoint allows you to update the username for your account.**<br/>
> <br/>
> Keeping your user profile up to date is important. This will help SendGrid to verify who you are as well as contact you should we need to.<br/>
> <br/>
> For more information about your user profile:<br/>
> <br/>
> * [SendGrid Account Settings](https://sendgrid.com/docs/User_Guide/Settings/account.html)

*Tags:* `Users API`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve Event Webhook settings

> **This endpoint allows you to retrieve your current event webhook settings.**<br/>
> <br/>
> If an event type is marked as `true`, then the event webhook will include information about that event.<br/>
> <br/>
> SendGrid's Event Webhook will notify a URL of your choice via HTTP POST with information about events that occur as SendGrid processes your email.<br/>
> <br/>
> Common uses of this data are to remove unsubscribes, react to spam reports, determine unengaged recipients, identify bounced email addresses, or create advanced analytics of your email program.

*Tags:* `Webhooks`

#### Input Parameters
* `on-behalf-of` - _optional_

### Update Event Notification Settings

> **This endpoint allows you to update your current event webhook settings.**<br/>
> <br/>
> If an event type is marked as `true`, then the event webhook will include information about that event.<br/>
> <br/>
> SendGrid's Event Webhook will notify a URL of your choice via HTTP POST with information about events that occur as SendGrid processes your email.<br/>
> <br/>
> Common uses of this data are to remove unsubscribes, react to spam reports, determine unengaged recipients, identify bounced email addresses, or create advanced analytics of your email program.

*Tags:* `Webhooks`

#### Input Parameters
* `on-behalf-of` - _optional_

### Test Event Notification Settings

> **This endpoint allows you to test your event webhook by sending a fake event notification post to the provided URL.**<br/>
> <br/>
> SendGrid's Event Webhook will notify a URL of your choice via HTTP POST with information about events that occur as SendGrid processes your email.<br/>
> <br/>
> Common uses of this data are to remove unsubscribes, react to spam reports, determine unengaged recipients, identify bounced email addresses, or create advanced analytics of your email program.

*Tags:* `Webhooks`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve all parse settings

> **This endpoint allows you to retrieve all of your current inbound parse settings.**<br/>
> <br/>
> The inbound parse webhook allows you to have incoming emails parsed, extracting some or all of the contnet, and then have that content POSTed by SendGrid to a URL of your choosing. For more information, please see our [User Guide](https://sendgrid.com/docs/API_Reference/Webhooks/parse.html).

*Tags:* `Settings - Inbound Parse`

#### Input Parameters
* `on-behalf-of` - _optional_

### Create a parse setting

> **This endpoint allows you to create a new inbound parse setting.**<br/>
> <br/>
> The inbound parse webhook allows you to have incoming emails parsed, extracting some or all of the content, and then have that content POSTed by SendGrid to a URL of your choosing. For more information, please see our [User Guide](https://sendgrid.com/docs/API_Reference/Webhooks/parse.html).

*Tags:* `Settings - Inbound Parse`

#### Input Parameters
* `on-behalf-of` - _optional_

### Delete a parse setting

> **This endpoint allows you to delete a specific inbound parse setting.**<br/>
> <br/>
> The inbound parse webhook allows you to have incoming emails parsed, extracting some or all of the contnet, and then have that content POSTed by SendGrid to a URL of your choosing. For more information, please see our [User Guide](https://sendgrid.com/docs/API_Reference/Webhooks/parse.html).

*Tags:* `Settings - Inbound Parse`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve a specific parse setting

> **This endpoint allows you to retrieve a specific inbound parse setting.**<br/>
> <br/>
> The inbound parse webhook allows you to have incoming emails parsed, extracting some or all of the contnet, and then have that content POSTed by SendGrid to a URL of your choosing. For more information, please see our [User Guide](https://sendgrid.com/docs/API_Reference/Webhooks/parse.html).

*Tags:* `Settings - Inbound Parse`

#### Input Parameters
* `on-behalf-of` - _optional_

### Update a parse setting

> **This endpoint allows you to update a specific inbound parse setting.**<br/>
> <br/>
> The inbound parse webhook allows you to have incoming emails parsed, extracting some or all of the contnet, and then have that content POSTed by SendGrid to a URL of your choosing. For more information, please see our [User Guide](https://sendgrid.com/docs/API_Reference/Webhooks/parse.html).

*Tags:* `Settings - Inbound Parse`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieves Inbound Parse Webhook statistics.

> **This endpoint allows you to retrieve the statistics for your Parse Webhook useage.**<br/>
> <br/>
> SendGrid's Inbound Parse Webhook allows you to parse the contents and attachments of incomming emails. The Parse API can then POST the parsed emails to a URL that you specify. The Inbound Parse Webhook cannot parse messages greater than 20MB in size, including all attachments.<br/>
> <br/>
> There are a number of pre-made integrations for the SendGrid Parse Webhook which make processing events easy. You can find these integrations in the [Library Index](https://sendgrid.com/docs/Integrate/libraries.html#-Webhook-Libraries).

*Tags:* `Webhooks`

#### Input Parameters
* `limit` - _optional_ - The number of statistics to return on each page.
* `offset` - _optional_ - The number of statistics to skip.
* `aggregated_by` - _optional_ - How you would like the statistics to by grouped. 
    Possible values: day, week, month.
* `start_date` - _required_ - The starting date of the statistics you want to retrieve. Must be in the format YYYY-MM-DD
* `end_date` - _optional_ - The end date of the statistics you want to retrieve. Must be in the format YYYY-MM-DD
* `on-behalf-of` - _optional_

### List all domain whitelabels.

> **This endpoint allows you to retrieve a list of all domain whitelabels you have created.**<br/>
> <br/>
> A domain whitelabel allows you to remove the "via" or "sent on behalf of" message that your recipients see when they read your emails. Whitelabeling a domain allows you to replace sendgrid.net with your personal sending domain. You will be required to create a subdomain so that SendGrid can generate the DNS records which you must give to your host provider. If you choose to use Automated Security, SendGrid will provide you with 3 CNAME records. If you turn Automated Security off, you will be given 2 TXT records and 1 MX record.<br/>
> <br/>
> For more information on whitelabeling, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/Whitelabel/index.html)

*Tags:* `Whitelabel - Domains`

#### Input Parameters
* `limit` - _optional_ - Number of domains to return.
* `offset` - _optional_ - Paging offset.
* `exclude_subusers` - _optional_ - Exclude subuser domains from the result.
* `username` - _optional_ - The username associated with a whitelabel.
* `domain` - _optional_ - Search for domain whitelabels that match the given domain.
* `on-behalf-of` - _optional_

### Create a domain whitelabel.

> **This endpoint allows you to create a whitelabel for one of your domains.**<br/>
> <br/>
> If you are creating a domain whitelabel that you would like a subuser to use, you have two options:<br/>
> 1. Use the "username" parameter. This allows you to create a whitelabel on behalf of your subuser. This means the subuser is able to see and modify the created whitelabel.<br/>
> 2. Use the Association workflow (see Associate Domain section). This allows you to assign a whitelabel created by the parent to a subuser. This means the subuser will default to the assigned whitelabel, but will not be able to see or modify that whitelabel. However, if the subuser creates their own whitelabel it will overwrite the assigned whitelabel.<br/>
> <br/>
> A domain whitelabel allows you to remove the "via" or "sent on behalf of" message that your recipients see when they read your emails. Whitelabeling a domain allows you to replace sendgrid.net with your personal sending domain. You will be required to create a subdomain so that SendGrid can generate the DNS records which you must give to your host provider. If you choose to use Automated Security, SendGrid will provide you with 3 CNAME records. If you turn Automated Security off, you will be given 2 TXT records and 1 MX record.<br/>
> <br/>
> For more information on whitelabeling, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/Whitelabel/index.html)

*Tags:* `Whitelabel - Domains`

#### Input Parameters
* `on-behalf-of` - _optional_

### Get the default domain whitelabel.

> **This endpoint allows you to retrieve the default whitelabel for a domain.**<br/>
> <br/>
> A domain whitelabel allows you to remove the "via" or "sent on behalf of" message that your recipients see when they read your emails. Whitelabeling a domain allows you to replace sendgrid.net with your personal sending domain. You will be required to create a subdomain so that SendGrid can generate the DNS records which you must give to your host provider. If you choose to use Automated Security, SendGrid will provide you with 3 CNAME records. If you turn Automated Security off, you will be given 2 TXT records and 1 MX record.<br/>
> <br/>
> For more information on whitelabeling, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/Whitelabel/index.html)<br/>
> <br/>
> ## URI Parameters<br/>
> | URI Parameter   | Type   | Description  |<br/>
> |---|---|---|<br/>
> | domain | string  |The domain to find a default domain whitelabel for. |

*Tags:* `Whitelabel - Domains`

#### Input Parameters
* `on-behalf-of` - _optional_

### Disassociate a domain whitelabel from a given user.

> **This endpoint allows you to disassociate a specific whitelabel from a subuser.**<br/>
> <br/>
> A domain whitelabel allows you to remove the "via" or "sent on behalf of" message that your recipients see when they read your emails. Whitelabeling a domain allows you to replace sendgrid.net with your personal sending domain. You will be required to create a subdomain so that SendGrid can generate the DNS records which you must give to your host provider. If you choose to use Automated Security, SendGrid will provide you with 3 CNAME records. If you turn Automated Security off, you will be given 2 TXT records and 1 MX record.<br/>
> <br/>
> Domain whitelabels can be associated with (i.e. assigned to) subusers from a parent account. This functionality allows subusers to send mail using their parent's whitelabels. To associate a whitelabel with a subuser, the parent account must first create the whitelabel and validate it. The the parent may then associate the whitelabel via the subuser management tools.<br/>
> <br/>
> For more information on whitelabeling, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/Whitelabel/index.html)<br/>
> <br/>
> ## URI Parameters<br/>
> | URI Parameter   | Type  | Required?  | Description  |<br/>
> |---|---|---|---|<br/>
> | username | string  | required  | Username for the subuser to find associated whitelabels for. |

*Tags:* `Whitelabel - Domains`

#### Input Parameters
* `on-behalf-of` - _optional_

### List the domain whitelabel associated with the given user.

> **This endpoint allows you to retrieve all of the whitelabels that have been assigned to a specific subuser.**<br/>
> <br/>
> A domain whitelabel allows you to remove the "via" or "sent on behalf of" message that your recipients see when they read your emails. Whitelabeling a domain allows you to replace sendgrid.net with your personal sending domain. You will be required to create a subdomain so that SendGrid can generate the DNS records which you must give to your host provider. If you choose to use Automated Security, SendGrid will provide you with 3 CNAME records. If you turn Automated Security off, you will be given 2 TXT records and 1 MX record.<br/>
> <br/>
> Domain whitelabels can be associated with (i.e. assigned to) subusers from a parent account. This functionality allows subusers to send mail using their parent's whitelabels. To associate a whitelabel with a subuser, the parent account must first create the whitelabel and validate it. The the parent may then associate the whitelabel via the subuser management tools.<br/>
> <br/>
> For more information on whitelabeling, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/Whitelabel/index.html)<br/>
> <br/>
> ## URI Parameters<br/>
> | URI Parameter   | Type  | Description  |<br/>
> |---|---|---|<br/>
> | username | string  | Username of the subuser to find associated whitelabels for. |

*Tags:* `Whitelabel - Domains`

#### Input Parameters
* `on-behalf-of` - _optional_

### Delete a domain whitelabel.

> **This endpoint allows you to delete a domain whitelabel.**<br/>
> <br/>
> A domain whitelabel allows you to remove the "via" or "sent on behalf of" message that your recipients see when they read your emails. Whitelabeling a domain allows you to replace sendgrid.net with your personal sending domain. You will be required to create a subdomain so that SendGrid can generate the DNS records which you must give to your host provider. If you choose to use Automated Security, SendGrid will provide you with 3 CNAME records. If you turn Automated Security off, you will be given 2 TXT records and 1 MX record.<br/>
> <br/>
> For more information on whitelabeling, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/Whitelabel/index.html)

*Tags:* `Whitelabel - Domains`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve a domain whitelabel.

> **This endpoint allows you to retrieve a specific domain whitelabel.**<br/>
> <br/>
> A domain whitelabel allows you to remove the "via" or "sent on behalf of" message that your recipients see when they read your emails. Whitelabeling a domain allows you to replace sendgrid.net with your personal sending domain. You will be required to create a subdomain so that SendGrid can generate the DNS records which you must give to your host provider. If you choose to use Automated Security, SendGrid will provide you with 3 CNAME records. If you turn Automated Security off, you will be given 2 TXT records and 1 MX record.<br/>
> <br/>
> For more information on whitelabeling, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/Whitelabel/index.html)

*Tags:* `Whitelabel - Domains`

#### Input Parameters
* `on-behalf-of` - _optional_

### Update a domain whitelabel.

> **This endpoint allows you to update the settings for a domain whitelabel.**<br/>
> <br/>
> A domain whitelabel allows you to remove the "via" or "sent on behalf of" message that your recipients see when they read your emails. Whitelabeling a domain allows you to replace sendgrid.net with your personal sending domain. You will be required to create a subdomain so that SendGrid can generate the DNS records which you must give to your host provider. If you choose to use Automated Security, SendGrid will provide you with 3 CNAME records. If you turn Automated Security off, you will be given 2 TXT records and 1 MX record.<br/>
> <br/>
> For more information on whitelabeling, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/Whitelabel/index.html)

*Tags:* `Whitelabel - Domains`

#### Input Parameters
* `on-behalf-of` - _optional_

### Associate a domain whitelabel with a given user.

> **This endpoint allows you to associate a specific domain whitelabel with a subuser.**<br/>
> <br/>
> A domain whitelabel allows you to remove the "via" or "sent on behalf of" message that your recipients see when they read your emails. Whitelabeling a domain allows you to replace sendgrid.net with your personal sending domain. You will be required to create a subdomain so that SendGrid can generate the DNS records which you must give to your host provider. If you choose to use Automated Security, SendGrid will provide you with 3 CNAME records. If you turn Automated Security off, you will be given 2 TXT records and 1 MX record.<br/>
> <br/>
> Domain whitelabels can be associated with (i.e. assigned to) subusers from a parent account. This functionality allows subusers to send mail using their parent's whitelabels. To associate a whitelabel with a subuser, the parent account must first create the whitelabel and validate it. The the parent may then associate the whitelabel via the subuser management tools.<br/>
> <br/>
> For more information on whitelabeling, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/Whitelabel/index.html)<br/>
> <br/>
> ## URI Parameters<br/>
> | URI Parameter   | Type   | Description  |<br/>
> |---|---|---|<br/>
> | domain_id | integer   | ID of the domain whitelabel to associate with the subuser. |

*Tags:* `Whitelabel - Domains`

#### Input Parameters
* `on-behalf-of` - _optional_

### Add an IP to a domain whitelabel.

> **This endpoint allows you to add an IP address to a domain whitelabel.**<br/>
> <br/>
> A domain whitelabel allows you to remove the "via" or "sent on behalf of" message that your recipients see when they read your emails. Whitelabeling a domain allows you to replace sendgrid.net with your personal sending domain. You will be required to create a subdomain so that SendGrid can generate the DNS records which you must give to your host provider. If you choose to use Automated Security, SendGrid will provide you with 3 CNAME records. If you turn Automated Security off, you will be given 2 TXT records and 1 MX record.<br/>
> <br/>
> For more information on whitelabeling, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/Whitelabel/index.html)<br/>
> <br/>
> ## URI Parameters<br/>
> | URI Parameter   | Type  |  Description  |<br/>
> |---|---|---|<br/>
> | id | integer  | ID of the domain to which you are adding an IP |

*Tags:* `Whitelabel - Domains`

#### Input Parameters
* `on-behalf-of` - _optional_

### Remove an IP from a domain whitelabel.

> **This endpoint allows you to remove a domain's IP address from that domain's whitelabel.**<br/>
> <br/>
> A domain whitelabel allows you to remove the "via" or "sent on behalf of" message that your recipients see when they read your emails. Whitelabeling a domain allows you to replace sendgrid.net with your personal sending domain. You will be required to create a subdomain so that SendGrid can generate the DNS records which you must give to your host provider. If you choose to use Automated Security, SendGrid will provide you with 3 CNAME records. If you turn Automated Security off, you will be given 2 TXT records and 1 MX record.<br/>
> <br/>
> For more information on whitelabeling, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/Whitelabel/index.html)<br/>
> <br/>
> ## URI Parameters<br/>
> | URI Parameter   | Type  | Description  |<br/>
> |---|---|---|<br/>
> | id | integer  | ID of the domain whitelabel to delete the IP from. |<br/>
> | ip | string | IP to remove from the domain whitelabel. |

*Tags:* `Whitelabel - Domains`

#### Input Parameters
* `on-behalf-of` - _optional_
* `ip` - _required_

### Validate a domain whitelabel.

> **This endpoint allows you to validate a domain whitelabel. If it fails, it will return an error message describing why the whitelabel could not be validated.**<br/>
> <br/>
> A domain whitelabel allows you to remove the "via" or "sent on behalf of" message that your recipients see when they read your emails. Whitelabeling a domain allows you to replace sendgrid.net with your personal sending domain. You will be required to create a subdomain so that SendGrid can generate the DNS records which you must give to your host provider. If you choose to use Automated Security, SendGrid will provide you with 3 CNAME records. If you turn Automated Security off, you will be given 2 TXT records and 1 MX record.<br/>
> <br/>
> For more information on whitelabeling, please see our [User Guide](https://sendgrid.com/docs/User_Guide/Settings/Whitelabel/index.html)<br/>
> <br/>
> ## URI Parameters<br/>
> | URI Parameter   | Type   | Description  |<br/>
> |---|---|---|<br/>
> | id | integer  |ID of the domain whitelabel to validate. |

*Tags:* `Whitelabel - Domains`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve all IP whitelabels

> **This endpoint allows you to retrieve all of the IP whitelabels that have been createdy by this account.**<br/>
> <br/>
> You may include a search key by using the "ip" parameter. This enables you to perform a prefix search for a given IP segment (e.g. "192.").<br/>
> <br/>
> A IP whitelabel consists of a subdomain and domain that will be used to generate a reverse DNS record for a given IP. Once SendGrid has verified that the appropriate A record for the IP has been created, the appropriate reverse DNS record for the IP is generated.<br/>
> <br/>
> For more information, please see our [User Guide](https://sendgrid.com/docs/API_Reference/Web_API_v3/Whitelabel/ips.html).

*Tags:* `Whitelabel - IPs`

#### Input Parameters
* `limit` - _optional_ - The number of results to retrieve.
* `offset` - _optional_ - The point in the list of results to begin retrieving IPs from.
* `ip` - _optional_ - The IP segment that you would like to use in a prefix search.
* `on-behalf-of` - _optional_

### Create an IP whitelabel

> **This endpoint allows you to create an IP whitelabel.**<br/>
> <br/>
> When creating an IP whitelable, you should use the same subdomain that you used when you created a domain whitelabel.<br/>
> <br/>
> A IP whitelabel consists of a subdomain and domain that will be used to generate a reverse DNS record for a given IP. Once SendGrid has verified that the appropriate A record for the IP has been created, the appropriate reverse DNS record for the IP is generated.<br/>
> <br/>
> For more information, please see our [User Guide](https://sendgrid.com/docs/API_Reference/Web_API_v3/Whitelabel/ips.html).

*Tags:* `Whitelabel - IPs`

#### Input Parameters
* `on-behalf-of` - _optional_

### Delete an IP whitelabel

> **This endpoint allows you to delete an IP whitelabel.**<br/>
> <br/>
> A IP whitelabel consists of a subdomain and domain that will be used to generate a reverse DNS record for a given IP. Once SendGrid has verified that the appropriate A record for the IP has been created, the appropriate reverse DNS record for the IP is generated.<br/>
> <br/>
> For more information, please see our [User Guide](https://sendgrid.com/docs/API_Reference/Web_API_v3/Whitelabel/ips.html).

*Tags:* `Whitelabel - IPs`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve an IP whitelabel

> **This endpoint allows you to retrieve an IP whitelabel.**<br/>
> <br/>
> A IP whitelabel consists of a subdomain and domain that will be used to generate a reverse DNS record for a given IP. Once SendGrid has verified that the appropriate A record for the IP has been created, the appropriate reverse DNS record for the IP is generated.<br/>
> <br/>
> For more information, please see our [User Guide](https://sendgrid.com/docs/API_Reference/Web_API_v3/Whitelabel/ips.html).

*Tags:* `Whitelabel - IPs`

#### Input Parameters
* `on-behalf-of` - _optional_

### Validate an IP whitelabel

> **This endpoint allows you to validate an IP whitelabel.**<br/>
> <br/>
> A IP whitelabel consists of a subdomain and domain that will be used to generate a reverse DNS record for a given IP. Once SendGrid has verified that the appropriate A record for the IP has been created, the appropriate reverse DNS record for the IP is generated.<br/>
> <br/>
> For more information, please see our [User Guide](https://sendgrid.com/docs/API_Reference/Web_API_v3/Whitelabel/ips.html).

*Tags:* `Whitelabel - IPs`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve all link whitelabels

> **This endpoint allows you to retrieve all link whitelabels.**<br/>
> <br/>
> Email link whitelabels allow all of the click-tracked links you send in your emails to include the URL of your domain instead of sendgrid.net.<br/>
> <br/>
> For more information, please see our [User Guide](https://sendgrid.com/docs/API_Reference/Web_API_v3/Whitelabel/links.html).

*Tags:* `Whitelabel - Links`

#### Input Parameters
* `limit` - _optional_ - Limits the number of results returned per page.
* `on-behalf-of` - _optional_

### Create a Link Whitelabel

> **This endpoint allows you to create a new link whitelabel.**<br/>
> <br/>
> Email link whitelabels allow all of the click-tracked links you send in your emails to include the URL of your domain instead of sendgrid.net.<br/>
> <br/>
> For more information, please see our [User Guide](https://sendgrid.com/docs/API_Reference/Web_API_v3/Whitelabel/links.html).

*Tags:* `Whitelabel - Links`

#### Input Parameters
* `limit` - _optional_ - Number of domains to return.
* `offset` - _optional_ - Paging offset.
* `on-behalf-of` - _optional_

### Retrieve a Default Link Whitelabel

> **This endpoint allows you to retrieve the default link whitelabel.**<br/>
> <br/>
> Default link whitelabel is the actual link whitelabel to be used when sending messages. If there are multiple link whitelabels, the default is determined by the following order:<br/>
> <ul><br/>
>   <li>Validated link whitelabels marked as "default"</li><br/>
>   <li>Legacy link whitelabels (migrated from the whitelabel wizard)</li><br/>
>   <li>Default SendGrid link whitelabel (i.e. 100.ct.sendgrid.net)</li><br/>
> </ul><br/>
> <br/>
> Email link whitelabels allow all of the click-tracked links you send in your emails to include the URL of your domain instead of sendgrid.net.<br/>
> <br/>
> For more information, please see our [User Guide](https://sendgrid.com/docs/API_Reference/Web_API_v3/Whitelabel/links.html).

*Tags:* `Whitelabel - Links`

#### Input Parameters
* `domain` - _optional_ - The domain to match against when finding a corresponding link whitelabel.
* `on-behalf-of` - _optional_

### Disassociate a Link Whitelabel

> **This endpoint allows you to disassociate a link whitelabel from a subuser.**<br/>
> <br/>
> Link whitelables can be associated with subusers from the parent account. This functionality allows<br/>
> subusers to send mail using their parent's linke whitelabels. To associate a link whitelabel, the parent account<br/>
> must first create a whitelabel and validate it. The parent may then associate that whitelabel with a subuser via the API or the Subuser Management page in the user interface.<br/>
> <br/>
> Email link whitelabels allow all of the click-tracked links you send in your emails to include the URL of your domain instead of sendgrid.net.<br/>
> <br/>
> For more information, please see our [User Guide](https://sendgrid.com/docs/API_Reference/Web_API_v3/Whitelabel/links.html).

*Tags:* `Whitelabel - Links`

#### Input Parameters
* `username` - _required_ - The username of the subuser account that you want to disassociate a link whitelabel from.
* `on-behalf-of` - _optional_

### Retrieve Associated Link Whitelabel

> **This endpoint allows you to retrieve the associated link whitelabel for a subuser.**<br/>
> <br/>
> Link whitelables can be associated with subusers from the parent account. This functionality allows<br/>
> subusers to send mail using their parent's linke whitelabels. To associate a link whitelabel, the parent account<br/>
> must first create a whitelabel and validate it. The parent may then associate that whitelabel with a subuser via the API or the Subuser Management page in the user interface.<br/>
> <br/>
> Email link whitelabels allow all of the click-tracked links you send in your emails to include the URL of your domain instead of sendgrid.net.<br/>
> <br/>
> For more information, please see our [User Guide](https://sendgrid.com/docs/API_Reference/Web_API_v3/Whitelabel/links.html).

*Tags:* `Whitelabel - Links`

#### Input Parameters
* `username` - _required_ - The username of the subuser to retrieve associated link whitelabels for.
* `on-behalf-of` - _optional_

### Delete a Link Whitelabel

> **This endpoint allows you to delete a link whitelabel.**<br/>
> <br/>
> Email link whitelabels allow all of the click-tracked links you send in your emails to include the URL of your domain instead of sendgrid.net.<br/>
> <br/>
> For more information, please see our [User Guide](https://sendgrid.com/docs/API_Reference/Web_API_v3/Whitelabel/links.html).

*Tags:* `Whitelabel - Links`

#### Input Parameters
* `on-behalf-of` - _optional_

### Retrieve a Link Whitelabel

> **This endpoint allows you to retrieve a specific link whitelabel.**<br/>
> <br/>
> Email link whitelabels allow all of the click-tracked links you send in your emails to include the URL of your domain instead of sendgrid.net.<br/>
> <br/>
> For more information, please see our [User Guide](https://sendgrid.com/docs/API_Reference/Web_API_v3/Whitelabel/links.html).

*Tags:* `Whitelabel - Links`

#### Input Parameters
* `on-behalf-of` - _optional_

### Update a Link Whitelabel

> **This endpoint allows you to update a specific link whitelabel. You can use this endpoint to change a link whitelabel's default status.**<br/>
> <br/>
> Email link whitelabels allow all of the click-tracked links you send in your emails to include the URL of your domain instead of sendgrid.net.<br/>
> <br/>
> For more information, please see our [User Guide](https://sendgrid.com/docs/API_Reference/Web_API_v3/Whitelabel/links.html).

*Tags:* `Whitelabel - Links`

#### Input Parameters
* `on-behalf-of` - _optional_

### Validate a Link Whitelabel

> **This endpoint allows you to validate a link whitelabel.**<br/>
> <br/>
> Email link whitelabels allow all of the click-tracked links you send in your emails to include the URL of your domain instead of sendgrid.net.<br/>
> <br/>
> For more information, please see our [User Guide](https://sendgrid.com/docs/API_Reference/Web_API_v3/Whitelabel/links.html).

*Tags:* `Whitelabel - Links`

#### Input Parameters
* `on-behalf-of` - _optional_

### Associate a Link Whitelabel

> **This endpoint allows you to associate a link whitelabel with a subuser account.**<br/>
> <br/>
> Link whitelables can be associated with subusers from the parent account. This functionality allows<br/>
> subusers to send mail using their parent's linke whitelabels. To associate a link whitelabel, the parent account<br/>
> must first create a whitelabel and validate it. The parent may then associate that whitelabel with a subuser via the API or the Subuser Management page in the user interface.<br/>
> <br/>
> Email link whitelabels allow all of the click-tracked links you send in your emails to include the URL of your domain instead of sendgrid.net.<br/>
> <br/>
> For more information, please see our [User Guide](https://sendgrid.com/docs/API_Reference/Web_API_v3/Whitelabel/links.html).

*Tags:* `Whitelabel - Links`

#### Input Parameters
* `on-behalf-of` - _optional_

## License

**flow**ground :- Telekom iPaaS / sendgrid-com-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
