# https://aws.amazon.com/apache-2-0/
# Static Website

The goal of this website is to support the learning of the Building Serverless Applications course.

This folder is designed to be uplaoded to S3, strictly following the instructions,

You may need to edit a config file. Simpy replace the `null` with with your content.

For example inside config.json you would replace

```JavaScript
		var G_API_GATEWAY_URL_STR = null;
```

with

```JavaScript

		var G_API_GATEWAY_URL_STR = "https://eois2fhvse.execute-api.us-east-1.amazonaws.com/test"
```
as per your need.


Then push that back up to the root of the website.

Thanks.