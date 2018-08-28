{
  "info": {
    "name": "Expedia",
    "_postman_id": "ad137642-5a69-4f82-827c-0b8b48c3179a",
    "description": "Expedia Mobile API Documentation. &lt;br&gt;&lt;font color=&quot;blue&quot;&gt; (Note: In case of authorization exception, just &lt;a href=&quot;/static/mobile/swaggerui/#!/User/signin-user&quot;&gt;Sign-In&lt;/a&gt;)&lt;/font&gt;",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "fa096f1a-f6c0-4a26-85da-36511907c0ef",
          "name": "flights-mobile-image",
          "request": {
            "url": "http://apim.expedia.com/x/api/mobile/image?imageCode=%7B%7D&imageHeight=%7B%7D&imageType=%7B%7D&imageWidth=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Mobile API Flight Mobile Image Operation"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "42a3cf81-22a4-4f31-9e55-cef7d90e0c13"
            }
          ]
        }
      ]
    }
  ]
}