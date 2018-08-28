{
  "info": {
    "name": "Expedia Create A Trip",
    "_postman_id": "6d1ef9b5-e51d-49c9-8cf2-4f099698acca",
    "description": "Mobile API Packages Create Trip operation",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "travel",
      "item": [
        {
          "id": "5a512d22-0153-49ab-bf81-f7dc9fa16ebb",
          "name": "packages-create-trip",
          "request": {
            "url": "http://apim.expedia.com/x/api/packages/createTrip",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "destinationId",
                  "value": "{}",
                  "disabled": false,
                  "description": "stubbed"
                },
                {
                  "key": "productKey",
                  "value": "{}",
                  "disabled": false,
                  "description": "The product ID (piid) of the package you would like to get hotel offers for"
                },
                {
                  "key": "roomOccupants[0].childGuestAge",
                  "value": "{}",
                  "disabled": false,
                  "description": "represents the age of a single child guest staying in this room"
                },
                {
                  "key": "roomOccupants[0].infantsInSeat",
                  "value": "{}",
                  "disabled": false,
                  "description": "Any infants in seat"
                },
                {
                  "key": "roomOccupants[0].numberOfAdultGuests",
                  "value": "{}",
                  "disabled": false,
                  "description": "Number of adults staying in this room (default: 1)"
                },
                {
                  "key": "roomOccupants[0].seniorCount",
                  "value": "{}",
                  "disabled": false,
                  "description": "Number of seniors staying in this room (default: 0)"
                },
                {
                  "key": "tripName",
                  "value": "{}",
                  "disabled": false,
                  "description": "stubbed"
                }
              ]
            },
            "description": "Mobile API Packages Create Trip operation"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b47dab7e-2814-4521-b6c2-b6999cbf7152"
            }
          ]
        }
      ]
    }
  ]
}