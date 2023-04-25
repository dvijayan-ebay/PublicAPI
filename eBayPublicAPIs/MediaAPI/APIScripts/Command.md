
## Overview: https://developer.ebay.com/api-docs/commerce/media/overview.html
### Create Video
#### Document reference : https://developer.ebay.com/api-docs/commerce/media/resources/video/methods/createVideo

```
curl -i --request POST 'https://apim.ebay.com/commerce/media/v1_beta/video' \
--header 'Authorization: Bearer <token>' \
--header 'X-EBAY-C-MARKETPLACE-ID: EBAY_US' \
--header 'Content-Type: application/json' \
--data-raw '{
    "size": "1783xxxx",
    "title": "Upload Testing",
    "description": "Upload Testing",
    "classification": [
        "ITEM"
    ]
}'
```
### Upload Video
#### Document reference : https://developer.ebay.com/api-docs/commerce/media/resources/video/methods/uploadVideo
```
curl -i --request POST 'https://apim.ebay.com/commerce/media/v1_beta/video/9a6fd8981870ab8e73344593xxxxxxxxx/upload' \
--header 'Authorization: Bearer <token>' \
--header 'X-EBAY-C-MARKETPLACE-ID: EBAY_US' \
--header 'Content-Type: application/octet-stream' \
--data-binary '@/Users/<path>/<file_name>'

```
### Get Video
#### Document reference : https://developer.ebay.com/api-docs/commerce/media/resources/video/methods/getVideo
```
curl -i --request GET 'https://apim.ebay.com/commerce/media/v1_beta/video/9a6fd8981870ab8e73344593xxxxxxxxx' \
--header 'Authorization: Bearer <token>' \
--header 'X-EBAY-C-MARKETPLACE-ID: EBAY_US' \'  
```

