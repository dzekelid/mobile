{
  "info": {
    "name": "Expedia Get Package Offers",
    "_postman_id": "d0229dcb-ec5b-439b-9c54-6be2d61a5d44",
    "description": "Mobile API Packages",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "54f622c5-20d4-4b92-a332-a19f22ca4a2f",
          "name": "packages-offers",
          "request": {
            "url": "http://apim.expedia.com/x/api/packages/hotelOffers?checkInDate=%7B%7D&checkOutDate=%7B%7D&childTravelerAge=%7B%7D&infantSeatingInLap=%7B%7D&numberOfAdultTravelers=%7B%7D&productKey=%7B%7D&ratePlanCode=%7B%7D&roomTypeCode=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Mobile API Packages"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1d3b4f80-eb7f-49f1-a8a3-556e2b8fd4be"
            }
          ]
        }
      ]
    }
  ]
}