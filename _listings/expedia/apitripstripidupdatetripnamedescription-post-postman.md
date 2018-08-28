{
  "info": {
    "name": "Expedia Update Trip Name and Description",
    "_postman_id": "65335b99-62e2-4092-a306-169c2c17e16a",
    "description": "Mobile API Trips update trip name and description operation",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "bdbf617e-65bd-49f4-8199-dcb81a6018ae",
          "name": "trips-update-trip",
          "request": {
            "url": {
              "protocol": "http",
              "host": "apim.expedia.com",
              "path": [
                "x",
                "api/trips/:tripId/updateTripNameDescription"
              ],
              "variable": [
                {
                  "id": "tripId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "tripname",
                  "value": "{}",
                  "disabled": false,
                  "description": "The name of the trip"
                },
                {
                  "key": "tripnote",
                  "value": "{}",
                  "disabled": false,
                  "description": "The comments of the trip"
                }
              ]
            },
            "description": "Mobile API Trips update trip name and description operation"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "83f52731-6553-496c-a918-cedfd5e974e7"
            }
          ]
        }
      ]
    }
  ]
}