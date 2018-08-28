{
  "info": {
    "name": "Microsoft Graph API Get Icon",
    "_postman_id": "8e326d40-2330-49bc-8f18-7a45e19e5e8b",
    "description": "Get Icon Retrieve the properties and relationships of icon object.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "icon",
      "item": [
        {
          "id": "e7553584-646e-4556-9dc0-6a26cc2362e2",
          "name": "GetIcon",
          "request": {
            "url": "http://graph.microsoft.com/workbook/worksheets(&lt;id|name&gt;)/tables(&lt;id|name&gt;)/sort/fields/icon",
            "method": "GET",
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
            "description": "Get Icon Retrieve the properties and relationships of icon object"
          },
          "response": [
            {
              "code": 200,
              "name": "Response_200",
              "id": "61dc1fdb-dc2d-4f6c-bdd1-8b479cccfafb"
            }
          ]
        }
      ]
    }
  ]
}