{
  "info": {
    "name": "Expedia",
    "_postman_id": "ccb6defd-5bbc-4f0b-a944-ac9120836d47",
    "description": "Expedia Mobile API Documentation. &lt;br&gt;&lt;font color=&quot;blue&quot;&gt; (Note: In case of authorization exception, just &lt;a href=&quot;/static/mobile/swaggerui/#!/User/signin-user&quot;&gt;Sign-In&lt;/a&gt;)&lt;/font&gt;",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "1e3ad653-7e57-4c4d-a791-0159b61c70ba",
          "name": "flights-create-trip",
          "request": {
            "url": "http://apim.expedia.com/x/api/flight/trip/create",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "fareFamilyCode",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "fareFamilyTotalPrice",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "mobileShoppingKey",
                  "value": "{}",
                  "disabled": false,
                  "description": "The mobile shopping key we are going to create a trip for"
                },
                {
                  "key": "productKey",
                  "value": "{}",
                  "disabled": false,
                  "description": "The product key, obtained from /api/flight/search, we are going to create a trip for"
                },
                {
                  "key": "qualifyAirAttach",
                  "value": "{}",
                  "disabled": false,
                  "description": "Whether to return a qualified air attach product for this trip"
                },
                {
                  "key": "tripTitle",
                  "value": "{}",
                  "disabled": false,
                  "description": "The name of this itinerary as it will appear to customer service and in the itinerary list"
                },
                {
                  "key": "withInsurance",
                  "value": "{}",
                  "disabled": false,
                  "description": "Whether to return the available insurance options for this trip"
                }
              ]
            },
            "description": "Mobile API Flights Create Trip Operation"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1b28db8c-9922-4fbf-97b9-bbcf127cb8f4"
            }
          ]
        }
      ]
    }
  ]
}