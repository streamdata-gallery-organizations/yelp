{
  "info": {
    "name": "Yelp Get Autocomplete",
    "_postman_id": "78d1e3da-5bad-4663-8e4f-4361abf76258",
    "description": "Get autocomplete.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Autocomplete",
      "item": [
        {
          "id": "389e8306-b0ce-442b-956a-42e641ecdd9e",
          "name": "getAutocomplete",
          "request": {
            "url": "http://api.yelp.com/v3/autocomplete?No Name=%7B%7D&text=%7B%7D",
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
            "description": "Get autocomplete."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "27ac543a-ac3a-4c48-ab0b-a8cf8559a079"
            }
          ]
        }
      ]
    }
  ]
}