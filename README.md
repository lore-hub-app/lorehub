This is a repository for the LoreHub's techical documentation.

 

# LoreHub

LoreHub is a web app that helps creates stories and build worlds.

[Link to LoreHub](https://lorehub.app)



## Dialog Schema

```javascript
  {
    dialog_id: "Guid as string",
    starting_node_id: "Guid as string",
    player_versions: ["1.5"],
    documents: [
      {
        id: "Guid as string",
        name: "string"
      }
    ],
    nodes: [
      {
        id: "Guid as string",
        next_node_id: "Guid as string",
        contents: [
          {
            id: "Guid as string",
            content_data_reference: {
              text: "string",
              document_id: "Guid as string"
            },
            content_data_text: null
          },
          {
            id: "Guid as string",
            content_data_reference: null,
            content_data_text: {
              text: "string"
            }
          }
        ]
      }
    ]
  }

```
