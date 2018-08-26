{
  "info": {
    "name": "Crypto Compare API Description",
    "_postman_id": "b5e1eb59-c7bb-422f-a3ab-d06262419ccf",
    "description": "Api description.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Discovery",
      "item": [
        {
          "id": "d94ed5bd-447d-40f7-ad15-2299aefabd0f",
          "name": "UnnammedEndpointGet",
          "request": {
            "url": "http://min-api.cryptocompare.com/",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Api description."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f3b04313-8d56-4d20-930f-e3ede8585671"
            }
          ]
        }
      ]
    }
  ]
}