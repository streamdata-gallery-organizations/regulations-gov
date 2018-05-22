{
  "info": {
    "name": "Regulations.gov Returns Document information",
    "_postman_id": "106d2369-770f-41ce-be31-72da0970e028",
    "description": "Returns Document information",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Regulations",
      "item": [
        {
          "id": "88667224-06c6-4fbf-a0de-22f9599c9dd3",
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
              "id": "44afb829-571a-434b-a5a3-28e571e3be43"
            }
          ]
        },
        {
          "id": "c18b8494-6ebc-4ef2-89e3-4ac82b123c00",
          "name": "getDocument.ResponseFormat",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.data.gov",
              "path": [
                "regulations",
                "v3",
                "document.:response_format"
              ],
              "query": [
                {
                  "key": "documentId",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "federalRegisterNumber",
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
            "description": "Returns Document information"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "26a7959d-477f-4ac7-85d7-615fe3940ed9"
            }
          ]
        }
      ]
    }
  ]
}