---
description: Learn how to import a collection into postman using cURL
---

# Import a collection using cURL

## About cURL

cURL is a computer software project providing a library and command-line tool for transferring data using various protocols.

## Import cURL

For this how to, the cURL to be imported is for generating a new oauth token using your app key and secret.

```text
curl -X POST -H "Content-Type: application/x-www-form-urlencoded" -u YOUR-APP-KEY:YOUR-SECRET -d 'grant_type=client_credentials' https://livelink.sapmobileservices.com/api/oauth/token
```

Importing a cURL is like importing a collection, with some minor differences:

* Open the postman app
* Click on "import" button

![](../.gitbook/assets/postman-import-collection%20%281%29.png)

* On the Import popup, select "Paste raw text" and paste the cURL for sending a message. 

![](../.gitbook/assets/postman-import-curl%20%281%29.png)

* After imported, the curl will appear in a new tab and most of the mandatory parameters will be already filled in. 

![](../.gitbook/assets/postman-imported-curl.png)

