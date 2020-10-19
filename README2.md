import urllib.request
from bs4 import BeautifulSoup
wiki = "http://jsonplaceholder.typicode.com/users"
page = urllib.request.urlopen(wiki)
soup = BeautifulSoup(page, 'html5lib')



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
