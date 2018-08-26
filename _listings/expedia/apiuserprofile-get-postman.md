{
  "info": {
    "name": "Expedia Profile",
    "_postman_id": "c116441a-662e-487e-9cb3-401b11c7d6f7",
    "description": "Mobile API User Profile",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "46c9ddcc-4097-4b05-87ff-ecf54d009da8",
          "name": "profile-user",
          "request": {
            "url": "http://apim.expedia.com/x/api/user/profile?profileTypes=%7B%7D&retrieveCoupons=%7B%7D&tuid=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Mobile API User Profile"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e18524cc-b2ca-471e-adc6-d75aa2438db2"
            }
          ]
        }
      ]
    }
  ]
}