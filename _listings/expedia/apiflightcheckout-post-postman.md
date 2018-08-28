{
  "info": {
    "name": "Expedia",
    "_postman_id": "b53d24ad-3ce7-4e65-8dda-787db2b8e061",
    "description": "Expedia Mobile API Documentation. &lt;br&gt;&lt;font color=&quot;blue&quot;&gt; (Note: In case of authorization exception, just &lt;a href=&quot;/static/mobile/swaggerui/#!/User/signin-user&quot;&gt;Sign-In&lt;/a&gt;)&lt;/font&gt;",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "91c0d4da-7018-462c-85c3-c7ab4d4d7f22",
          "name": "flights-checkout",
          "request": {
            "url": "http://apim.expedia.com/x/api/flight/checkout",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "associatedFlightPassengers[0].birthDate",
                  "value": "{}",
                  "disabled": false,
                  "description": "Birth date of the associated flight passenger fields"
                },
                {
                  "key": "associatedFlightPassengers[0].gender",
                  "value": "{}",
                  "disabled": false,
                  "description": "Gender of the associated flight passenger fields"
                },
                {
                  "key": "associatedFlightPassengers[0].knownTravelerNumber",
                  "value": "{}",
                  "disabled": false,
                  "description": "knownTravelerNumber(PreCheckNumber) of the associated flight passenger fields"
                },
                {
                  "key": "associatedFlightPassengers[0].passengerCategory",
                  "value": "{}",
                  "disabled": false,
                  "description": ":Passenger category of the associated flight passenger fields"
                },
                {
                  "key": "associatedFlightPassengers[0].passportCountryCode",
                  "value": "{}",
                  "disabled": false,
                  "description": "Passport country code of the associated flight passenger fields"
                },
                {
                  "key": "associatedFlightPassengers[0].seatPreference",
                  "value": "{}",
                  "disabled": false,
                  "description": "Seat preference of the associated flight passenger fields"
                },
                {
                  "key": "associatedFlightPassengers[0].seats[0].arrivalAirportCode",
                  "value": "{}",
                  "disabled": false,
                  "description": "The arrival airport code for the selected seat of the associated flight passenger fields"
                },
                {
                  "key": "associatedFlightPassengers[0].seats[0].departureAirportCode",
                  "value": "{}",
                  "disabled": false,
                  "description": "The departure airport code for the selected seat of the associated flight passenger fields"
                },
                {
                  "key": "associatedFlightPassengers[0].seats[0].seatNumber",
                  "value": "{}",
                  "disabled": false,
                  "description": "Selected Seat Number of the associated flight passenger fields"
                },
                {
                  "key": "associatedFlightPassengers[0].specialAssistanceOption",
                  "value": "{}",
                  "disabled": false,
                  "description": "Special assistance option for the associated flight passenger fields"
                },
                {
                  "key": "associatedFlightPassengers[0].title",
                  "value": "{}",
                  "disabled": false,
                  "description": "Title of the associated flight passenger fields"
                },
                {
                  "key": "associatedFlightPassengers[0].TSARedressNumber",
                  "value": "{}",
                  "disabled": false,
                  "description": "TSA redress number of the associated flight passenger fields"
                },
                {
                  "key": "birthDate",
                  "value": "{}",
                  "disabled": false,
                  "description": "Birth date of the associated flight passenger fields"
                },
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
                  "key": "email",
                  "value": "{}",
                  "disabled": false,
                  "description": "Email address of the main flight passenger"
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
                  "description": "Three letter 4217 ISO currency code of the expected credit card fee"
                },
                {
                  "key": "expectedFareCurrencyCode",
                  "value": "{}",
                  "disabled": false,
                  "description": "Three letter 4217 ISO currency code of the expected total price"
                },
                {
                  "key": "expectedTotalFare",
                  "value": "{}",
                  "disabled": false,
                  "description": "The expected total price of the trip, matching exactly whatever the user last saw"
                },
                {
                  "key": "expediaEmailOptIn",
                  "value": "{}",
                  "disabled": false,
                  "description": "If the main flight passenger wishes to opt out for Expedia emails or not"
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
                  "key": "firstName",
                  "value": "{}",
                  "disabled": false,
                  "description": "The first name of the traveler"
                },
                {
                  "key": "frequentFlyerDetails[0].flightAirlineCode",
                  "value": "{}",
                  "disabled": false,
                  "description": "Airline code for the flight to be booked"
                },
                {
                  "key": "frequentFlyerDetails[0].frequentFlyerPlanAirlineCode",
                  "value": "{}",
                  "disabled": false,
                  "description": "Airline code for the airline whose frequent Flyer programme is to be used"
                },
                {
                  "key": "frequentFlyerDetails[0].frequentFlyerPlanCode",
                  "value": "{}",
                  "disabled": false,
                  "description": "Plan code for Airline program"
                },
                {
                  "key": "frequentFlyerDetails[0].membershipNumber",
                  "value": "{}",
                  "disabled": false,
                  "description": "User specific membership number for the frequent flyer programme"
                },
                {
                  "key": "gender",
                  "value": "{}",
                  "disabled": false,
                  "description": "Gender of the associated flight passenger fields"
                },
                {
                  "key": "knownTravelerNumber",
                  "value": "{}",
                  "disabled": false,
                  "description": "knownTravelerNumber(PreCheckNumber) of the associated flight passenger fields"
                },
                {
                  "key": "lastName",
                  "value": "{}",
                  "disabled": false,
                  "description": "The last name of the traveler"
                },
                {
                  "key": "mainFlightPassenger[0].email",
                  "value": "{}",
                  "disabled": false,
                  "description": "Email address of the main flight passenger"
                },
                {
                  "key": "mainFlightPassenger[0].expediaEmailOptIn",
                  "value": "{}",
                  "disabled": false,
                  "description": "If the main flight passenger wishes to opt out for Expedia emails or not"
                },
                {
                  "key": "mainFlightPassenger[0].password",
                  "value": "{}",
                  "disabled": false,
                  "description": "Password of the main flight passenger"
                },
                {
                  "key": "mainFlightPassenger[0].phone",
                  "value": "{}",
                  "disabled": false,
                  "description": "Phone number of the main flight passenger"
                },
                {
                  "key": "mainFlightPassenger[0].phoneCountryCode",
                  "value": "{}",
                  "disabled": false,
                  "description": "Country code of the phone of the main flight passenger"
                },
                {
                  "key": "middleName",
                  "value": "{}",
                  "disabled": false,
                  "description": "The middle name of the traveler"
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
                  "key": "passengerCategory",
                  "value": "{}",
                  "disabled": false,
                  "description": ":Passenger category of the associated flight passenger fields"
                },
                {
                  "key": "passportCountryCode",
                  "value": "{}",
                  "disabled": false,
                  "description": "Passport country code of the associated flight passenger fields"
                },
                {
                  "key": "password",
                  "value": "{}",
                  "disabled": false,
                  "description": "Password of the main flight passenger"
                },
                {
                  "key": "phone",
                  "value": "{}",
                  "disabled": false,
                  "description": "Phone number of the main flight passenger"
                },
                {
                  "key": "phoneCountryCode",
                  "value": "{}",
                  "disabled": false,
                  "description": "Country code of the phone of the main flight passenger"
                },
                {
                  "key": "postalCode",
                  "value": "{}",
                  "disabled": false,
                  "description": "The postal code of the traveler's billing address"
                },
                {
                  "key": "prettyPrint",
                  "value": "{}",
                  "disabled": false,
                  "description": "If true, return JSON with tabs, spaces and newlines to be human readable"
                },
                {
                  "key": "seatPreference",
                  "value": "{}",
                  "disabled": false,
                  "description": "Seat preference of the associated flight passenger fields"
                },
                {
                  "key": "seats[0].arrivalAirportCode",
                  "value": "{}",
                  "disabled": false,
                  "description": "The arrival airport code for the selected seat of the Main flight passenger fields"
                },
                {
                  "key": "seats[0].departureAirportCode",
                  "value": "{}",
                  "disabled": false,
                  "description": "The departure airport code for the selected seat of the Main flight passenger fields"
                },
                {
                  "key": "seats[0].seatNumber",
                  "value": "{}",
                  "disabled": false,
                  "description": "Selected Seat Number of the Main flight passenger fields"
                },
                {
                  "key": "sendEmailConfirmation",
                  "value": "{}",
                  "disabled": false,
                  "description": "Used to check if confirmation email needs to be sent or not"
                },
                {
                  "key": "specialAssistanceOption",
                  "value": "{}",
                  "disabled": false,
                  "description": "Special assistance option for the associated flight passenger fields"
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
                  "key": "suppressFinalBooking",
                  "value": "{}",
                  "disabled": false,
                  "description": "If true, do not actually charge for and book the trip, stop after creating the itinerary"
                },
                {
                  "key": "tealeafTransactionId",
                  "value": "{}",
                  "disabled": false,
                  "description": "The unique transaction ID used in TeaLeaf PSR tracking"
                },
                {
                  "key": "title",
                  "value": "{}",
                  "disabled": false,
                  "description": "Title of the associated flight passenger fields"
                },
                {
                  "key": "tripId",
                  "value": "{}",
                  "disabled": false,
                  "description": "The trip ID of an existing trip, from /api/flight/trip/create"
                },
                {
                  "key": "TSARedressNumber",
                  "value": "{}",
                  "disabled": false,
                  "description": "TSA redress number of the associated flight passenger fields"
                },
                {
                  "key": "validateWithChildren",
                  "value": "{}",
                  "disabled": false,
                  "description": "Set this flag to true to enable child validation logic on the server"
                }
              ]
            },
            "description": "Checkout a previously created flight trip, requiring payment fields, the trip id, and the passenger fields"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "42ecb69e-b2b4-4b8e-baba-2a2eb04fbd36"
            }
          ]
        }
      ]
    }
  ]
}