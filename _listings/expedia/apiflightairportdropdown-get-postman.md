{
  "info": {
    "name": "Expedia",
    "_postman_id": "c86c8abf-39bb-40ce-bc1c-c6cbcab51f40",
    "description": "Expedia Mobile API Documentation. &lt;br&gt;&lt;font color=&quot;blue&quot;&gt; (Note: In case of authorization exception, just &lt;a href=&quot;/static/mobile/swaggerui/#!/User/signin-user&quot;&gt;Sign-In&lt;/a&gt;)&lt;/font&gt;",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "b7b84f3e-57d7-4058-8d5d-00591dd248d9",
          "name": "flights-airport-dropdown",
          "request": {
            "url": "http://apim.expedia.com/x/api/flight/airportDropDown",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Mobile API Flight Airport Dropdown Operation"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "889107ee-5f9d-4f22-b65e-6cea343bceff"
            }
          ]
        }
      ]
    }
  ]
}