{
  "info": {
    "name": "Expedia",
    "_postman_id": "c9c6d843-8e39-4bce-b0dd-862062acf3d2",
    "description": "Expedia Mobile API Documentation. &lt;br&gt;&lt;font color=&quot;blue&quot;&gt; (Note: In case of authorization exception, just &lt;a href=&quot;/static/mobile/swaggerui/#!/User/signin-user&quot;&gt;Sign-In&lt;/a&gt;)&lt;/font&gt;",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "6458b98d-4fcd-4c41-a9a5-9560c6fc4d79",
          "name": "flights-details",
          "request": {
            "url": "http://apim.expedia.com/x/api/flight/details?arrivalAirport=%7B%7D&childTravelerAge=%7B%7D&departureAirport=%7B%7D&departureDate=%7B%7D&infantSeatingInLap=%7B%7D&numberOfAdultTravelers=%7B%7D&productKey=%7B%7D&returnDate=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Mobile API Flight Details Operation"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0fe7aea0-f6b2-4cf5-a6ba-00a0b0381075"
            }
          ]
        }
      ]
    }
  ]
}