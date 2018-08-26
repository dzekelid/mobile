{
  "info": {
    "name": "Expedia Update",
    "_postman_id": "388dae55-780c-42d4-8316-1fbab9840750",
    "description": "Mobile API User Update Traveler",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "115d65bf-9bcb-4a32-90b1-3cc3a130af11",
          "name": "update-traveler",
          "request": {
            "url": "http://apim.expedia.com/x/api/user/update-traveler",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "birthDate",
                  "value": "{}",
                  "disabled": false,
                  "description": "TSA required field; passenger's birth date"
                },
                {
                  "key": "email",
                  "value": "{}",
                  "disabled": false,
                  "description": "This passenger's email address"
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
                  "description": "The first name of the traveler"
                },
                {
                  "key": "gender",
                  "value": "{}",
                  "disabled": false,
                  "description": "TSA required field, MALE or FEMALE"
                },
                {
                  "key": "knownTravelerNumber",
                  "value": "{}",
                  "disabled": false,
                  "description": "Passenger's knownTravelerNumber(PreCheckNumber), a 9 digit number"
                },
                {
                  "key": "lastName",
                  "value": "{}",
                  "disabled": false,
                  "description": "The last name of the traveler"
                },
                {
                  "key": "middleName",
                  "value": "{}",
                  "disabled": false,
                  "description": "The middle name of the traveler"
                },
                {
                  "key": "passengerCategory",
                  "value": "{}",
                  "disabled": false,
                  "description": "The passenger's category"
                },
                {
                  "key": "passportCountryCode",
                  "value": "{}",
                  "disabled": false,
                  "description": "Passport country, UPPERCASE three letter country code"
                },
                {
                  "key": "password",
                  "value": "{}",
                  "disabled": false,
                  "description": "The password provided by the Expedia user"
                },
                {
                  "key": "phone",
                  "value": "{}",
                  "disabled": false,
                  "description": "The phone number of the traveler"
                },
                {
                  "key": "phoneCountryCode",
                  "value": "{}",
                  "disabled": false,
                  "description": "The country code of the phone number of the traveler"
                },
                {
                  "key": "seatPreference",
                  "value": "{}",
                  "disabled": false,
                  "description": "Passenger's seat preference"
                },
                {
                  "key": "specialAssistanceOption",
                  "value": "{}",
                  "disabled": false,
                  "description": "Special assistance choice"
                },
                {
                  "key": "title",
                  "value": "{}",
                  "disabled": false,
                  "description": "Title of passenger"
                },
                {
                  "key": "TSARedressNumber",
                  "value": "{}",
                  "disabled": false,
                  "description": "Passenger's TSA redress number, which is, in theory a 7 digit number"
                }
              ]
            },
            "description": "Mobile API User Update Traveler"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f2e3112b-c621-4148-8c6a-9feea10d21fa"
            }
          ]
        }
      ]
    }
  ]
}