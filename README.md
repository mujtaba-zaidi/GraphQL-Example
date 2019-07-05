#  GraphQL-Example

####  How to run server
* npm run start

#### Querying GraphQL server

1. Go to url "http://localhost:4000/graphql"

2. Getting data
  * To get all values
    `query { customers { id } }` or enter the available values.
  * To get single customer
    `query { customer(id: "1"){name}}`
