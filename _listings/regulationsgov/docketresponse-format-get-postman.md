{
  "info": {
    "name": "Regulations.gov Returns Docket information",
    "_postman_id": "1b153a7e-b9ca-4a88-aab2-b9a419fa80de",
    "description": "Returns Docket information",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Regulations",
      "item": [
        {
          "id": "5dde14e2-6748-45ff-b71b-e0be8d79b217",
          "name": "getDocket.ResponseFormat",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.data.gov",
              "path": [
                "regulations",
                "v3",
                "docket.:response_format"
              ],
              "query": [
                {
                  "key": "docketId",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "response_format",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns Docket information"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "65b48065-1a41-4af3-bb07-fa4fee82d043"
            }
          ]
        }
      ]
    }
  ]
}