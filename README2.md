mutation {
  listUsers(input: {
    Id: [{
      Id_primario: {
        id: 
        name: ""
        username: ""
        email: ""

      }
    }]
      }
      address: {
        street: ""
        suite: ""
        city: ""
        zipcode: ""
        "geo": {
        "lat": "",
        "lng": ""
          }
      },
       "phone": "",
       "website": "",
       "company": {
       "name": "",
       "catchPhrase": "",
      "bs": ""
    }    
    }]
  }) {
    success
     name{
      id
      username
    }
    Users {
      id
      email {
        id
        status
          {
          index
          indexDisplay
        }
        {
          index
          indexDisplay
          
        }
      }
    }
    errors {
      field
      message
    }
  }
}
