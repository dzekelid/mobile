{
  "info": {
    "name": "Expedia",
    "_postman_id": "1a2a43e0-5d3a-41aa-90db-86c5daa6f782",
    "description": "Expedia Mobile API Documentation. &lt;br&gt;&lt;font color=&quot;blue&quot;&gt; (Note: In case of authorization exception, just &lt;a href=&quot;/static/mobile/swaggerui/#!/User/signin-user&quot;&gt;Sign-In&lt;/a&gt;)&lt;/font&gt;",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "5fa3e977-b0e1-42d6-9377-8747dc071223",
          "name": "flights-search",
          "request": {
            "url": "http://apim.expedia.com/x/api/flight/search?arrivalAirport=%7B%7D&childTravelerAge=%7B%7D&correlationId=%7B%7D&departureAirport=%7B%7D&departureDate=%7B%7D&featureOverride=%7B%7D&infantSeatingInLap=%7B%7D&lccAndMerchantFareCheckoutAllowed=%7B%7D&maxOfferCount=%7B%7D&nonStopFlight=%7B%7D&numberOfAdultTravelers=%7B%7D&prettyPrint=%7B%7D&returnDate=%7B%7D&showRefundableFlight=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Mobile API Flights"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e9014547-997b-4d6b-bfad-798b99b9c1a4"
            }
          ]
        }
      ]
    }
  ]
}