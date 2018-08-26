{
  "info": {
    "name": "Network API List Partent",
    "_postman_id": "43df4779-df6c-4316-8a0e-81554f6b20f8",
    "description": "lists the parent network of a given network.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Networks",
      "item": [
        {
          "id": "8c27afe5-2a2d-445a-9f51-72c3d20442ab",
          "name": "nets",
          "request": {
            "url": "http://example.com/api/nets?handle=handle&name=name",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Networks"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5955d3d4-5327-40e1-bab1-89fe8c8ba34b"
            }
          ]
        }
      ]
    },
    {
      "name": "POCs",
      "item": [
        {
          "id": "ffc464b3-e473-47ff-b9e8-357f681f578b",
          "name": "netsPocs",
          "request": {
            "url": "http://example.com/api/net/pocs",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "lists the POCs associated with a given network."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1e8c13f5-2cfc-4ab5-ac9d-6d3a9a25b4a9"
            }
          ]
        }
      ]
    },
    {
      "name": "Parent",
      "item": [
        {
          "id": "d146cb3c-ba54-4376-9547-1d33619803ab",
          "name": "netParent",
          "request": {
            "url": "http://example.com/api/net/parent",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "lists the parent network of a given network."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7198f437-084e-4b50-a1d5-c5d1b8072290"
            }
          ]
        }
      ]
    }
  ]
}