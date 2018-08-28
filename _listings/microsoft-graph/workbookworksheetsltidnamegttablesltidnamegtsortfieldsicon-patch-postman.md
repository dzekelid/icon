{
  "info": {
    "name": "Microsoft Graph API Update Icon",
    "_postman_id": "9d72f91b-88ca-45d1-9b4e-bda0a8b16931",
    "description": "Update icon Update the properties of icon object.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "icon",
      "item": [
        {
          "id": "0666a968-a09b-46d5-addd-6e727f1b39ea",
          "name": "UpdateIcon",
          "request": {
            "url": "http://graph.microsoft.com/workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/sort/fields/icon",
            "method": "PATCH",
            "header": [
              {
                "key": "Authorization",
                "value": "{}",
                "description": "Bearer",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Update icon Update the properties of icon object"
          },
          "response": [
            {
              "code": 200,
              "name": "Response_200",
              "id": "c2ac73cb-7436-4593-88a8-e254dbcfbae4"
            }
          ]
        }
      ]
    }
  ]
}