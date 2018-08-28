{
  "info": {
    "name": "Expedia",
    "_postman_id": "14967307-db92-4e4d-b7de-1ef98ddc2a2a",
    "description": "Expedia Mobile API Documentation. &lt;br&gt;&lt;font color=&quot;blue&quot;&gt; (Note: In case of authorization exception, just &lt;a href=&quot;/static/mobile/swaggerui/#!/User/signin-user&quot;&gt;Sign-In&lt;/a&gt;)&lt;/font&gt;",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "b4f3b07b-26da-4791-a636-425786cee8f2",
          "name": "flights-image",
          "request": {
            "url": "http://apim.expedia.com/x/api/flight/image?destinationCode=%7B%7D&imageHeight=%7B%7D&imageWidth=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Mobile API Flight Image Operation"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "245c391d-1ee7-4710-895c-67a9b54171df"
            }
          ]
        }
      ]
    }
  ]
}