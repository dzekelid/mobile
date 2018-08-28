{
  "info": {
    "name": "Expedia User Sign-In",
    "_postman_id": "a405b5c5-8bb2-4c93-8d29-69c66d8f21d9",
    "description": "Mobile API User Sign-In",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "08c89cb5-16dc-4cc6-988b-7947e41c4eec",
          "name": "signin-user",
          "request": {
            "url": "http://apim.expedia.com/x/api/user/sign-in",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "email",
                  "value": "{}",
                  "disabled": false,
                  "description": "Email Address"
                },
                {
                  "key": "firstTimeSigin",
                  "value": "{}",
                  "disabled": false,
                  "description": "Boolean to indicate if this is a first time sign-in"
                },
                {
                  "key": "guestLoginWithItin",
                  "value": "{}",
                  "disabled": false,
                  "description": "When logging in with an Itin Number and Email set this field to True"
                },
                {
                  "key": "includeFullPaymentProfile",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                },
                {
                  "key": "itinNumber",
                  "value": "{}",
                  "disabled": false,
                  "description": "The Itinerary Number can be used instead of a password to authenticate the user"
                },
                {
                  "key": "password",
                  "value": "{}",
                  "disabled": false,
                  "description": "User Password"
                },
                {
                  "key": "profileOnly",
                  "value": "{}",
                  "disabled": false,
                  "description": "If true, don't provide username/password fields and just re-retrieve the currently signed on user's profile"
                },
                {
                  "key": "profileTypes",
                  "value": "{}",
                  "disabled": false,
                  "description": "This is a comma-separated list of profile types to retrieve when the login is processed"
                },
                {
                  "key": "retrieveCoupons",
                  "value": "{}",
                  "disabled": false,
                  "description": "Whether to include user coupons in the response"
                },
                {
                  "key": "staySignedIn",
                  "value": "{}",
                  "disabled": false,
                  "description": "Sign Me In checkbox"
                }
              ]
            },
            "description": "Mobile API User Sign-In"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ec362436-a4e7-476a-b441-388bcb0cfd65"
            }
          ]
        }
      ]
    }
  ]
}