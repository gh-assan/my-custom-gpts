Here is the data structure for the dashboard representation 

```json
{
  "dashboard": {
    "title": "string",
    "description": "string",
    "theme": {
      "colorScheme": "string",
      "fontStyle": "string"
    },
    "layout": {
      "type": "grid | freeform",
      "rows": "integer",
      "columns": "integer"
    },
    "sections": [
      {
        "id": "unique_identifier",
        "title": "string",
        "description": "string",
        "layout": {
          "type": "grid | freeform",
          "rows": "integer",
          "columns": "integer",
          "position": {
            "x": "integer",
            "y": "integer"
          },
          "size": {
            "width": "percentage | pixels",
            "height": "percentage | pixels"
          }
        },
        "widgets": [
          {
            "id": "unique_identifier",
            "type": "chart | graph | table | text | image | custom_widget",
            "title": "string",
            "description": "string",
            "appearance": {
              "color": "string",
              "size": {
                "width": "percentage | pixels",
                "height": "percentage | pixels"
              },
              "fontStyle": "string"
            },
            "position": {
              "x": "integer",
              "y": "integer"
            }
          }
        ]
      }
    ]
  }
}
```