{
  "title": "Rule",
  "description": "",
  "weight": 1,
  "fields": [
    {
      "typeString": "String!",
      "name": "id",
      "url": "/hotel-x/reference/scalars/string",
      "description": "rule identifier",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "String",
      "name": "name",
      "url": "/hotel-x/reference/scalars/string",
      "description": "rule name",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "MarkupRuleType!",
      "name": "type",
      "url": "/hotel-x/reference/enums/markupruletype",
      "description": "type of the value",
      "isDeprecated": false,
      "args": null
    },
    {
      "typeString": "Float!",
      "name": "value",
      "url": "/hotel-x/reference/scalars/float",
      "description": "value applied by this rule",
      "isDeprecated": false,
      "args": null
    }
  ],
  "requireby": null,
  "enumValues": null,
  "operator": "type",
  "typename": "Rule",
  "hideGithubLink": true
}
## GraphQL schema definition

{{% graphql-schema-type %}}

## Fields

{{% graphql-field %}}
