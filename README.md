# Takeout Documentation


<table style="width:100%"><caption>Exported Object: Activity records <br>Exported Object represents: Timestamped records of your activity across different Google Products <br>Object is exported in these formats:HTML JSON 
<br>Exported object has the following fields:<br></caption><tfoot><tr><td colspan="10"> * Data fields produced in an export vary by service and user action and some services and/or actions do not produce each data field described.</td></tr></tfoot><tr><th width="25%">Data Field</th><th width="60%">Field Definition</th><th width="15%">Data Field Type</th></tr><tr><td>header</td><td>This will typically be either an app name, domain name, or product name. <br><br> Example: <br> YouTube: YouTube <br> Search: Domain name or Search <br> Chrome: Chrome</td><td>string</td></tr><tr><td>title</td><td>High level summary of the user activity. <br><br> Example: <br> YouTube: Watched..., Subscribed to..., Visited, ... <br> Search: Searched for ..., Viewed ..., Visited ... <br> Chrome: Visited ...</td><td>string</td></tr><tr><td>titleUrl</td><td>URL. <br><br> Example: <br> YouTube: youtube url <br> Search: Searched, Visited, Viewed url <br> Chrome: Visited url</td><td>string</td></tr><tr><td>subtitles</td><td>Detailed user activity. <br><br> Example: <br> YouTube: Channel information name and url, ...</td><td>string</td></tr><tr><td>description</td><td>Extra information that helps explain the activity.</td><td>string</td></tr><tr><td>time</td><td>Time and date the user did the activity.</td><td>string</td></tr><tr><td>products</td><td>The Products that this data is a part of. <br><br> Example: <br> YouTube: Youtube <br> Search: Search <br> Chrome: Chrome</td><td>list</td></tr><tr><td>details</td><td>Used to display information about where the user activity comes from, such as if the user activity was the result of the user interacting with an ad or app. <br><br> Example: <br> YouTube: &quot;From Google Ads&quot;</td><td>string</td></tr><tr><td>activityControls</td><td>Some common Google data collection settings (like Location History and Web &amp; App Activity) that this data is part of. <br><br> Example: <br> YouTube: YouTube watch history, YouTube search history <br> Search: Web App Activity <br> Chrome: Additional Web App Activity.</td><td>string</td></tr><tr><td>locationInfo</td><td>The location(s) associated with this activity.</td><td>string</td></tr><tr><td>imageFile</td><td>The local file name for the image attachment.</td><td>string</td></tr><tr><td>audioFiles</td><td>The list of local file name for the audio attachments..</td><td>list</td></tr></table><table style="width:100%"><caption>Exported Object: Image attachments <br>Exported Object represents: Images related to your activity records <br>Object is exported in these formats:JPEG 
</caption><tfoot><tr><td colspan="10"> * Data fields produced in an export vary by service and user action and some services and/or actions do not produce each data field described.</td></tr></tfoot><tr><th width="25%"></th><th width="60%"></th><th width="15%"></th>        </tr></table><table style="width:100%"><caption>Exported Object: Audio attachments <br>Exported Object represents: Audio files related to your activity records <br>Object is exported in these formats:MPEG 
</caption><tfoot><tr><td colspan="10"> * Data fields produced in an export vary by service and user action and some services and/or actions do not produce each data field described.</td></tr></tfoot><tr><th width="25%"></th><th width="60%"></th><th width="15%"></th>        </tr></table>


Please click [here](https://support.google.com/accounts/contact/takeout_feedback?sjid=10260094094251490988-NA) to provide feedback.

This repository is updated periodically.
