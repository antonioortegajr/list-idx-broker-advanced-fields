# list-idx-broker-advanced-fields
Use the IDX Broker API to list all advanced fields and field values.

Standard Disclaimer: This code is not official IDX Broker code. It does use their API, but in NO WAY is it supported by IDX Broker. DO NOT contact IDX Broker for any support of this code.

These files preform an API call to get all advanced fields available in a particular MLS.

You will need:

an IDX Broker API key

the IDX Broker value for the MLS. Example: a000

The advanced_fileds_search.php will then populate the page with a list of available advanced search fields for the specified MLS. Each field will be a link that passes the API key and search field name to values.php and will display the values available for the specified field.
