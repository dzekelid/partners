{
  "info": {
    "name": "GoToAssist Remote Support Partner-System Link Info",
    "_postman_id": "a6b1cb3c-7a4c-474a-8796-4e5a8a165cf4",
    "description": "This method retrieves all partner-system links that are registered for a given domain. These links are used by GoToAssist to make calls back to the partner system to enable the creation of tickets during support sessions.\n\n  Request Parameters                    \n                      \n    field        data type      description    \n    systemDomain        string      The domain name of the partner system.    \n                      \n\n\n  Response Parameters: (* Optional)                  \n                    \n    field      data type      description    \n    systemName      string      The human-readable name of the partner system (may be displayed to the user in the GoToAssist web application); it is used to uniquely identify partner systems, along with the systemDomain for a particular user    \n    systemDomain      string      The domain name of the partner system; it is used to uniquely identify partner systems, along with the systemName for a particular user    \n    userEmail      string      The email address of the user these links are for    \n    userToken      string      A unique identifier generated by the partner system that will be used to authenticate requests made by GoToAssist on behalf of this user    \n    callbackURL      string      The callback URL into the partner system    \n                    \n\nStatus Codes              \n              \n    Staus Code      description    \n    200 OK      The information was successfully retrieved    \n    400 Bad Request      An error occurred due to a missing systemDomain parameter    \n    401 Unauthorized      An authentication parameter was passed, but either it was invalid or the technician is not entitled with a Remote Support seat    \n    500 Internal Server Error      An unhandled error occurred",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Partner-System",
      "item": [
        {
          "id": "aa8ae335-406f-4c2e-9671-c69f157590b9",
          "name": "SystemLinksGet",
          "request": {
            "url": "http://api.getgo.com/G2A/rest/v1/systemLinks?systemDomain=%7B%7D",
            "method": "GET",
            "header": [
              {
                "key": "Accept",
                "value": "{}",
                "description": "",
                "disabled": false
              },
              {
                "key": "Content-Type",
                "value": "{}",
                "description": "",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "This method retrieves all partner-system links that are registered for a given domain. These links are used by GoToAssist to make calls back to the partner system to enable the creation of tickets during support sessions.\n\n  Request Parameters                    \n                      \n    field        data type      description    \n    systemDomain        string      The domain name of the partner system.    \n                      \n\n\n  Response Parameters: (* Optional)                  \n                    \n    field      data type      description    \n    systemName      string      The human-readable name of the partner system (may be displayed to the user in the GoToAssist web application); it is used to uniquely identify partner systems, along with the systemDomain for a particular user    \n    systemDomain      string      The domain name of the partner system; it is used to uniquely identify partner systems, along with the systemName for a particular user    \n    userEmail      string      The email address of the user these links are for    \n    userToken      string      A unique identifier generated by the partner system that will be used to authenticate requests made by GoToAssist on behalf of this user    \n    callbackURL      string      The callback URL into the partner system    \n                    \n\nStatus Codes              \n              \n    Staus Code      description    \n    200 OK      The information was successfully retrieved    \n    400 Bad Request      An error occurred due to a missing systemDomain parameter    \n    401 Unauthorized      An authentication parameter was passed, but either it was invalid or the technician is not entitled with a Remote Support seat    \n    500 Internal Server Error      An unhandled error occurred"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9b128f36-82cf-4123-8004-cf64a555ff62"
            }
          ]
        }
      ]
    }
  ]
}