{
  "info": {
    "name": "Expedia",
    "_postman_id": "3cc900c7-9470-41ef-ab3e-38967b6acb64",
    "description": "Expedia Mobile API Documentation. &lt;br&gt;&lt;font color=&quot;blue&quot;&gt; (Note: In case of authorization exception, just &lt;a href=&quot;/static/mobile/swaggerui/#!/User/signin-user&quot;&gt;Sign-In&lt;/a&gt;)&lt;/font&gt;",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "725e1819-150c-4fbd-be49-e395bc1162bc",
          "name": "packages-remove-coupon",
          "request": {
            "url": "http://apim.expedia.com/x/api/m/trip/remove/coupon",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "tripId",
                  "value": "{}",
                  "disabled": false,
                  "description": "The tripId we are going to apply the coupon to"
                }
              ]
            },
            "description": "Mobile API Packages Remove Coupon"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fcbc26dd-e152-41b1-ae5d-3a3792e0c184"
            }
          ]
        }
      ]
    }
  ]
}