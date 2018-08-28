{
  "info": {
    "name": "Expedia Create User",
    "_postman_id": "60f850da-9270-4581-8daa-0b1a2e315b82",
    "description": "Mobile API User Create",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "e7544f58-7749-4293-9ec8-79fa7368ee3d",
          "name": "create-user",
          "request": {
            "url": "http://apim.expedia.com/x/api/user/create",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "email",
                  "value": "{}",
                  "disabled": false,
                  "description": "Users email address"
                },
                {
                  "key": "enrollInLoyalty",
                  "value": "{}",
                  "disabled": false,
                  "description": "Whether to enroll the user in loyalty"
                },
                {
                  "key": "expediaEmailOptIn",
                  "value": "{}",
                  "disabled": false,
                  "description": "Whether to opt-in the user's email to travel deals"
                },
                {
                  "key": "firstName",
                  "value": "{}",
                  "disabled": false,
                  "description": "Users first name"
                },
                {
                  "key": "lastName",
                  "value": "{}",
                  "disabled": false,
                  "description": "Users last name"
                },
                {
                  "key": "middleName",
                  "value": "{}",
                  "disabled": false,
                  "description": "Users middle name"
                },
                {
                  "key": "password",
                  "value": "{}",
                  "disabled": false,
                  "description": "Users password"
                }
              ]
            },
            "description": "Mobile API User Create"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "33e5451c-bca3-4102-8f0e-444bef63f3f3"
            }
          ]
        }
      ]
    }
  ]
}