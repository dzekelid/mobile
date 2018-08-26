---
swagger: "2.0"
x-collection-name: Expedia
x-complete: 0
info:
  title: Expedia Mobile Flight Checkout
  description: Checkout a previously created flight trip, requiring payment fields,
    the trip id, and the passenger fields
  version: 0.0.1
host: apim.expedia.com
basePath: x/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/flight/airportDropDown:
    get:
      summary: Airport Dropdown
      description: Mobile API Flight Airport Dropdown Operation
      operationId: flights-airport-dropdown
      x-api-path-slug: apiflightairportdropdown-get
      responses:
        200:
          description: OK
      tags:
      - Travel
      - Airports
      - Airplanes
      - Airlines
  /api/flight/checkout:
    post:
      summary: Mobile Flight Checkout
      description: Checkout a previously created flight trip, requiring payment fields,
        the trip id, and the passenger fields
      operationId: flights-checkout
      x-api-path-slug: apiflightcheckout-post
      parameters:
      - in: formData
        name: associatedFlightPassengers[0].birthDate
        description: Birth date of the associated flight passenger fields
      - in: formData
        name: associatedFlightPassengers[0].gender
        description: Gender of the associated flight passenger fields
      - in: formData
        name: associatedFlightPassengers[0].knownTravelerNumber
        description: knownTravelerNumber(PreCheckNumber) of the associated flight
          passenger fields
      - in: formData
        name: associatedFlightPassengers[0].passengerCategory
        description: :Passenger category of the associated flight passenger fields
      - in: formData
        name: associatedFlightPassengers[0].passportCountryCode
        description: Passport country code of the associated flight passenger fields
      - in: formData
        name: associatedFlightPassengers[0].seatPreference
        description: Seat preference of the associated flight passenger fields
      - in: formData
        name: associatedFlightPassengers[0].seats[0].arrivalAirportCode
        description: The arrival airport code for the selected seat of the associated
          flight passenger fields
      - in: formData
        name: associatedFlightPassengers[0].seats[0].departureAirportCode
        description: The departure airport code for the selected seat of the associated
          flight passenger fields
      - in: formData
        name: associatedFlightPassengers[0].seats[0].seatNumber
        description: Selected Seat Number of the associated flight passenger fields
      - in: formData
        name: associatedFlightPassengers[0].specialAssistanceOption
        description: Special assistance option for the associated flight passenger
          fields
      - in: formData
        name: associatedFlightPassengers[0].title
        description: Title of the associated flight passenger fields
      - in: formData
        name: associatedFlightPassengers[0].TSARedressNumber
        description: TSA redress number of the associated flight passenger fields
      - in: formData
        name: birthDate
        description: Birth date of the associated flight passenger fields
      - in: formData
        name: city
        description: The city of the travelers billing address
      - in: formData
        name: country
        description: The 3 letter country code of the travelers billing address
      - in: formData
        name: creditCardNumber
        description: The credit card number used for this booking, if checking out
          with a new card
      - in: formData
        name: cvv
        description: The CVV of the travelers credit card used for this booking
      - in: formData
        name: doIThinkImSignedIn
        description: As a client I am checking-out with the assumption that I am signed
          in
      - in: formData
        name: email
        description: Email address of the main flight passenger
      - in: formData
        name: expectedCardFee
        description: The expected credit card fee, as returned by the createTrip call
          in the validFormsOfPayment object for whatever credit card the user is paying
          with
      - in: formData
        name: expectedCardFeeCurrencyCode
        description: Three letter 4217 ISO currency code of the expected credit card
          fee
      - in: formData
        name: expectedFareCurrencyCode
        description: Three letter 4217 ISO currency code of the expected total price
      - in: formData
        name: expectedTotalFare
        description: The expected total price of the trip, matching exactly whatever
          the user last saw
      - in: formData
        name: expediaEmailOptIn
        description: If the main flight passenger wishes to opt out for Expedia emails
          or not
      - in: formData
        name: expirationDateMonth
        description: The expiration date month of the credit card used for this booking
      - in: formData
        name: expirationDateYear
        description: The 4 digit expiration date year of the credit card used for
          this booking
      - in: formData
        name: firstName
        description: The first name of the traveler
      - in: formData
        name: frequentFlyerDetails[0].flightAirlineCode
        description: Airline code for the flight to be booked
      - in: formData
        name: frequentFlyerDetails[0].frequentFlyerPlanAirlineCode
        description: Airline code for the airline whose frequent Flyer programme is
          to be used
      - in: formData
        name: frequentFlyerDetails[0].frequentFlyerPlanCode
        description: Plan code for Airline program
      - in: formData
        name: frequentFlyerDetails[0].membershipNumber
        description: User specific membership number for the frequent flyer programme
      - in: formData
        name: gender
        description: Gender of the associated flight passenger fields
      - in: formData
        name: knownTravelerNumber
        description: knownTravelerNumber(PreCheckNumber) of the associated flight
          passenger fields
      - in: formData
        name: lastName
        description: The last name of the traveler
      - in: formData
        name: mainFlightPassenger[0].email
        description: Email address of the main flight passenger
      - in: formData
        name: mainFlightPassenger[0].expediaEmailOptIn
        description: If the main flight passenger wishes to opt out for Expedia emails
          or not
      - in: formData
        name: mainFlightPassenger[0].password
        description: Password of the main flight passenger
      - in: formData
        name: mainFlightPassenger[0].phone
        description: Phone number of the main flight passenger
      - in: formData
        name: mainFlightPassenger[0].phoneCountryCode
        description: Country code of the phone of the main flight passenger
      - in: formData
        name: middleName
        description: The middle name of the traveler
      - in: formData
        name: nameOnCard
        description: The card holders name
      - in: formData
        name: omniturePartnerId
        description: Omniture partner identification string
      - in: formData
        name: passengerCategory
        description: :Passenger category of the associated flight passenger fields
      - in: formData
        name: passportCountryCode
        description: Passport country code of the associated flight passenger fields
      - in: formData
        name: password
        description: Password of the main flight passenger
      - in: formData
        name: phone
        description: Phone number of the main flight passenger
      - in: formData
        name: phoneCountryCode
        description: Country code of the phone of the main flight passenger
      - in: formData
        name: postalCode
        description: The postal code of the travelers billing address
      - in: formData
        name: prettyPrint
        description: If true, return JSON with tabs, spaces and newlines to be human
          readable
      - in: formData
        name: seatPreference
        description: Seat preference of the associated flight passenger fields
      - in: formData
        name: seats[0].arrivalAirportCode
        description: The arrival airport code for the selected seat of the Main flight
          passenger fields
      - in: formData
        name: seats[0].departureAirportCode
        description: The departure airport code for the selected seat of the Main
          flight passenger fields
      - in: formData
        name: seats[0].seatNumber
        description: Selected Seat Number of the Main flight passenger fields
      - in: formData
        name: sendEmailConfirmation
        description: Used to check if confirmation email needs to be sent or not
      - in: formData
        name: specialAssistanceOption
        description: Special assistance option for the associated flight passenger
          fields
      - in: formData
        name: state
        description: The state (or province) of the travelers billing address
      - in: formData
        name: storeCreditCardInUserProfile
        description: Indicates whether to save the credit card information as a stored
          credit card in the user profile
      - in: formData
        name: storedCreditCardId
        description: The GUID for the stored credit card information to be used for
          payment
      - in: formData
        name: streetAddress
        description: The street part of the credit card owners billing address
      - in: formData
        name: streetAddress2
        description: Apartment or suite number of the travelers billing address
      - in: formData
        name: suppressFinalBooking
        description: If true, do not actually charge for and book the trip, stop after
          creating the itinerary
      - in: formData
        name: tealeafTransactionId
        description: The unique transaction ID used in TeaLeaf PSR tracking
      - in: formData
        name: title
        description: Title of the associated flight passenger fields
      - in: formData
        name: tripId
        description: The trip ID of an existing trip, from /api/flight/trip/create
      - in: formData
        name: TSARedressNumber
        description: TSA redress number of the associated flight passenger fields
      - in: formData
        name: validateWithChildren
        description: Set this flag to true to enable child validation logic on the
          server
      responses:
        200:
          description: OK
      tags:
      - Travel
      - Airports
      - Airplanes
      - Airlines
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---