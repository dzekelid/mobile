{
  "info": {
    "name": "Expedia",
    "_postman_id": "3872fde7-a616-4622-b868-e27da18e0f6b",
    "description": "Expedia Mobile API Documentation. &lt;br&gt;&lt;font color=&quot;blue&quot;&gt; (Note: In case of authorization exception, just &lt;a href=&quot;/static/mobile/swaggerui/#!/User/signin-user&quot;&gt;Sign-In&lt;/a&gt;)&lt;/font&gt;",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "612da699-1def-47b7-b2ac-54c5400ac345",
          "name": "packages-apply-coupon",
          "request": {
            "url": "http://apim.expedia.com/x/api/m/trip/coupon",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "coupon.code",
                  "value": "{}",
                  "disabled": false,
                  "description": "Coupon Code"
                },
                {
                  "key": "coupon.instanceId",
                  "value": "{}",
                  "disabled": false,
                  "description": "Instance ID"
                },
                {
                  "key": "coupon.name",
                  "value": "{}",
                  "disabled": false,
                  "description": "Coupon Name"
                },
                {
                  "key": "tripId",
                  "value": "{}",
                  "disabled": false,
                  "description": "The tripId we are going to apply the coupon to"
                }
              ]
            },
            "description": "Mobile API Packages Apply Coupon"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b1c72435-b6b0-4b41-80d0-c23f69ca2d5e"
            }
          ]
        }
      ]
    }
  ]
}