{
  "info": {
    "name": "Microsoft Graph API Update Icon",
    "_postman_id": "f619176b-928f-4675-ad18-17452f4c924e",
    "description": "Update icon Update the properties of icon object.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "icon",
      "item": [
        {
          "id": "23e6e295-2181-4967-a49c-62369baf58a7",
          "name": "UpdateIcon",
          "request": {
            "url": "http://graph.microsoft.com/workbook/tables(&lt;id|name&gt;)/sort/fields/icon",
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
              "id": "174d7573-36e8-43c4-9232-85bf7abb5f6a"
            }
          ]
        }
      ]
    }
  ]
}