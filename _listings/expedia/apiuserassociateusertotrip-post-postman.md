{
  "info": {
    "name": "Expedia Associate User To Trip",
    "_postman_id": "71a88c42-934b-4242-be2e-328490530fc0",
    "description": "Mobile API User Associate To Trip",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "08b9a0f0-8b26-4cd5-9fcf-df836f9f70a0",
          "name": "user-associate-to-trip",
          "request": {
            "url": "http://apim.expedia.com/x/api/user/associateUserToTrip",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "foo",
                  "value": "{}",
                  "disabled": false,
                  "description": "stubbed"
                }
              ]
            },
            "description": "Mobile API User Associate To Trip"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "058f0eeb-c23d-47b0-8222-b8fb64e54d65"
            }
          ]
        }
      ]
    }
  ]
}