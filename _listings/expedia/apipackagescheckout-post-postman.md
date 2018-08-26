{
  "info": {
    "name": "Expedia Checkout",
    "_postman_id": "06297fb9-4aa5-4dc2-8a2f-2af9930a0395",
    "description": "Mobile API Packages Checkout",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "1da84e06-f2b5-4b65-a112-7be38a62ac60",
          "name": "packages-checkout",
          "request": {
            "url": "http://apim.expedia.com/x/api/packages/checkout",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "city",
                  "value": "{}",
                  "disabled": false,
                  "description": "The city of the traveler's billing address"
                },
                {
                  "key": "country",
                  "value": "{}",
                  "disabled": false,
                  "description": "The 3 letter country code of the traveler's billing address"
                },
                {
                  "key": "creditCardNumber",
                  "value": "{}",
                  "disabled": false,
                  "description": "The credit card number used for this booking, if checking out with a new card"
                },
                {
                  "key": "cvv",
                  "value": "{}",
                  "disabled": false,
                  "description": "The CVV of the traveler's credit card used for this booking"
                },
                {
                  "key": "doIThinkImSignedIn",
                  "value": "{}",
                  "disabled": false,
                  "description": "As a client I am checking-out with the assumption that I am signed in"
                },
                {
                  "key": "expectedCardFee",
                  "value": "{}",
                  "disabled": false,
                  "description": "The expected credit card fee, as returned by the createTrip call in the validFormsOfPayment object for whatever credit card the user is paying with"
                },
                {
                  "key": "expectedCardFeeCurrencyCode",
                  "value": "{}",
                  "disabled": false,
                  "description": "Three letter 4217 ISO currency code of the expected total price"
                },
                {
                  "key": "expectedFareCurrencyCode",
                  "value": "{}",
                  "disabled": false,
                  "description": "Three letter 4217 ISO currency code of the expected credit card fee"
                },
                {
                  "key": "expectedTotalFare",
                  "value": "{}",
                  "disabled": false,
                  "description": "The expected total price of the trip, matching exactly whatever the user last saw"
                },
                {
                  "key": "expirationDateMonth",
                  "value": "{}",
                  "disabled": false,
                  "description": "The expiration date month of the credit card used for this booking"
                },
                {
                  "key": "expirationDateYear",
                  "value": "{}",
                  "disabled": false,
                  "description": "The 4 digit expiration date year of the credit card used for this booking"
                },
                {
                  "key": "flight[0].associatedFlightPassengers[0].birthDate",
                  "value": "{}",
                  "disabled": false,
                  "description": "Birth date of the associated flight passenger fields"
                },
                {
                  "key": "flight[0].associatedFlightPassengers[0].gender",
                  "value": "{}",
                  "disabled": false,
                  "description": "Gender of the associated flight passenger fields"
                },
                {
                  "key": "flight[0].associatedFlightPassengers[0].knownTravelerNumber",
                  "value": "{}",
                  "disabled": false,
                  "description": "knownTravelerNumber(PreCheckNumber) of the associated flight passenger fields"
                },
                {
                  "key": "flight[0].associatedFlightPassengers[0].passengerCategory",
                  "value": "{}",
                  "disabled": false,
                  "description": ":Passenger category of the associated flight passenger fields"
                },
                {
                  "key": "flight[0].associatedFlightPassengers[0].passportCountryCode",
                  "value": "{}",
                  "disabled": false,
                  "description": "Passport country code of the associated flight passenger fields"
                },
                {
                  "key": "flight[0].associatedFlightPassengers[0].seatPreference",
                  "value": "{}",
                  "disabled": false,
                  "description": "Seat preference of the associated flight passenger fields"
                },
                {
                  "key": "flight[0].associatedFlightPassengers[0].specialAssistanceOption",
                  "value": "{}",
                  "disabled": false,
                  "description": "Special assistance option for the associated flight passenger fields"
                },
                {
                  "key": "flight[0].associatedFlightPassengers[0].title",
                  "value": "{}",
                  "disabled": false,
                  "description": "Title of the associated flight passenger fields"
                },
                {
                  "key": "flight[0].associatedFlightPassengers[0].TSARedressNumber",
                  "value": "{}",
                  "disabled": false,
                  "description": "TSA redress number of the associated flight passenger fields"
                },
                {
                  "key": "flight[0].mainFlightPassenger[0].email",
                  "value": "{}",
                  "disabled": false,
                  "description": "Email address of the main flight passenger"
                },
                {
                  "key": "flight[0].mainFlightPassenger[0].expediaEmailOptIn",
                  "value": "{}",
                  "disabled": false,
                  "description": "If the main flight passenger wishes to opt out for Expedia emails or not"
                },
                {
                  "key": "flight[0].mainFlightPassenger[0].password",
                  "value": "{}",
                  "disabled": false,
                  "description": "Password of the main flight passenger"
                },
                {
                  "key": "flight[0].mainFlightPassenger[0].phone",
                  "value": "{}",
                  "disabled": false,
                  "description": "Phone number of the main flight passenger"
                },
                {
                  "key": "flight[0].mainFlightPassenger[0].phoneCountryCode",
                  "value": "{}",
                  "disabled": false,
                  "description": "Country code of the phone of the main flight passenger"
                },
                {
                  "key": "hotel[0].bedTypeId",
                  "value": "{}",
                  "disabled": false,
                  "description": "Indicates the selected bed Type"
                },
                {
                  "key": "hotel[0].primaryContactFullName",
                  "value": "{}",
                  "disabled": false,
                  "description": "Full name of the person who will be checking in"
                },
                {
                  "key": "nameOnCard",
                  "value": "{}",
                  "disabled": false,
                  "description": "The card holder's name"
                },
                {
                  "key": "omniturePartnerId",
                  "value": "{}",
                  "disabled": false,
                  "description": "Omniture partner identification string"
                },
                {
                  "key": "postalCode",
                  "value": "{}",
                  "disabled": false,
                  "description": "The postal code of the traveler's billing address"
                },
                {
                  "key": "sendEmailConfirmation",
                  "value": "{}",
                  "disabled": false,
                  "description": "Used to check if confirmation email needs to be sent or not"
                },
                {
                  "key": "state",
                  "value": "{}",
                  "disabled": false,
                  "description": "The state (or province) of the traveler's billing address"
                },
                {
                  "key": "storeCreditCardInUserProfile",
                  "value": "{}",
                  "disabled": false,
                  "description": "Indicates whether to save the credit card information as a stored credit card in the user profile"
                },
                {
                  "key": "storedCreditCardId",
                  "value": "{}",
                  "disabled": false,
                  "description": "The GUID for the stored credit card information to be used for payment"
                },
                {
                  "key": "streetAddress",
                  "value": "{}",
                  "disabled": false,
                  "description": "The street part of the credit card owner's billing address"
                },
                {
                  "key": "streetAddress2",
                  "value": "{}",
                  "disabled": false,
                  "description": "Apartment or suite number of the traveler's billing address"
                },
                {
                  "key": "tealeafTransactionId",
                  "value": "{}",
                  "disabled": false,
                  "description": "The unique transaction ID used in TeaLeaf PSR tracking"
                },
                {
                  "key": "tripId",
                  "value": "{}",
                  "disabled": false,
                  "description": "The trip ID of an existing trip, from /api/packages/createTrip"
                }
              ]
            },
            "description": "Mobile API Packages Checkout"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f43ce4c3-cdc5-4dea-8c8b-faf94a38924f"
            }
          ]
        }
      ]
    }
  ]
}