http:// http://jsonplaceholder.typicode.com/users


mutation {
	listUsers(input: {
			Id: 1
			Id_primario[{
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
	name {

 }
    errors {
      field
      message
    }
  }
}
