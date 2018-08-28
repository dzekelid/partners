{
  "info": {
    "name": "IDX Broker Get Partners Clients",
    "_postman_id": "1c9991c5-b48b-4d6d-8f4e-673105e3ffa8",
    "description": "A list of clients available to a given partner. The list of clients can be filtered by GET values.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Partners",
      "item": [
        {
          "id": "f8b32fee-77b0-4ac5-bab1-4a005ff6e33f",
          "name": "PartnersClientsGet",
          "request": {
            "url": "http://example.com/partners/clients",
            "method": "GET",
            "header": [
              {
                "key": "accesskey",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "apiversion",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "outputtype",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "A list of clients available to a given partner. The list of clients can be filtered by GET values."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5d4ea31d-852f-4e47-aa1b-5bbcea136c7f"
            }
          ]
        }
      ]
    }
  ]
}