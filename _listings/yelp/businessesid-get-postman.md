{
  "info": {
    "name": "Yelp Get Businesses",
    "_postman_id": "dd9875e4-c945-403b-8cc6-751db39a3d48",
    "description": "Get businesses.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Businesses",
      "item": [
        {
          "id": "0438322d-4814-4021-a4a4-b5de20ec444f",
          "name": "getBusinessesSearch",
          "request": {
            "url": "http://api.yelp.com/v3/businesses/search?No Name=%7B%7D&term=%7B%7D",
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
            "description": "Get businesses search."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1c000c83-14f0-4f9b-b816-533d8cd1d5b4"
            }
          ]
        },
        {
          "id": "d55863a0-b5d5-4e49-9337-d6f173933c32",
          "name": "getBusinesses",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.yelp.com",
              "path": [
                "v3",
                "businesses/:id"
              ],
              "query": [
                {
                  "key": "No Name",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "id",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
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
            "description": "Get businesses."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d5b42ed3-1280-4404-b96f-6e4ac812316e"
            }
          ]
        }
      ]
    }
  ]
}