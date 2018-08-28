{
  "info": {
    "name": "Expedia Trips by tripId",
    "_postman_id": "9faf7aeb-04c4-4ce1-b51d-a27bde777420",
    "description": "Mobile API Trips",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "67c766f8-c737-4907-876d-8290da86c14a",
          "name": "trips-search-id",
          "request": {
            "url": {
              "protocol": "http",
              "host": "apim.expedia.com",
              "path": [
                "x",
                "api/trips/:tripId"
              ],
              "query": [
                {
                  "key": "currencyCode",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "decimalPlaceCount",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "decorator",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "email",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "expectedAmount",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "useCache",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "tripId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Mobile API Trips"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5061856b-de8c-4dbf-8a15-9a953cf39336"
            }
          ]
        }
      ]
    }
  ]
}