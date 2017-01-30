# RestMongoDBSpringData

To create a new Traveler, POST a request with a body similar to the following example to the service (http://localhost:8080/people):

{
  "firstName" : "John", 
  "lastName"  : "Baggins",
  "addresses": [
      {
        "street": "123 Main St.",
        "city": "New York"
      },
      {
        "street": "456 Jones Ave",
        "city": "Denver"
      }
    ]
}

