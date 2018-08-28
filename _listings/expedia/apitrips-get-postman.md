{
  "info": {
    "name": "Expedia Get Trips",
    "_postman_id": "36f3021f-92b0-469e-be24-9c2fef2a9073",
    "description": "Mobile API Trips",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "c954ec08-41e8-4922-9a22-083c38d204e9",
          "name": "trips-search",
          "request": {
            "url": "http://apim.expedia.com/x/api/trips?filterBookingStatus=%7B%7D&filterLineOfBusiness=%7B%7D&filterTimePeriod=%7B%7D&getCachedDetails=%7B%7D&sort=%7B%7D",
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
              "id": "ac58b599-4c17-4889-84f1-ea6b096a8170"
            }
          ]
        }
      ]
    }
  ]
}