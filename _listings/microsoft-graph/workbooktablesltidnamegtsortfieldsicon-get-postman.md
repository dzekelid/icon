{
  "info": {
    "name": "Microsoft Graph API Get Icon",
    "_postman_id": "819aa78a-2dff-4a08-a591-b711c5239bf9",
    "description": "Get Icon Retrieve the properties and relationships of icon object.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "icon",
      "item": [
        {
          "id": "ef82dc91-b5b4-4a96-a8e3-50884ff73f6c",
          "name": "GetIcon",
          "request": {
            "url": "http://graph.microsoft.com/workbook/tables(&lt;id|name&gt;)/sort/fields/icon",
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
              "id": "c3dfed34-2ad1-4f5b-b16d-e93978aa1706"
            }
          ]
        }
      ]
    }
  ]
}