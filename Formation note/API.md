## REST API Request Structure :
- ##### domain/endpoint(?query=value&query2=value)
	- ###### Endpoint
		- The endpoint is like the root. Each endpoints have its utility, and we'll receive a different response according to them (see the docs)
	- ###### Query
		- They are the key values that an API can request to complete your request. (ex : filters etc) ; you can seperate them by using & 
		- The first query is after an ?
		- ###### It's usually for searching and filtering response
	- ###### Path Parameter
		- These are some additional infos about the path that we can add ex (id) : ![[brave_P23zSxuEPW.png]]
		- This id on the right is a path parameter, we have the endpoints activity followed by a specific id here
		- ###### It's usualy for identify a ressource according to some datas

https://learngitbranching.js.org/


### Make API Request | Axios

- #### Syntax : 
Config object : url, headers, params, base url (optionals )
DOCUMENTATIONS : https://axios-http.com/docs/intro
### GET REQUEST![[screenshot-www.udemy.com-2023.08.06-18_06_41.png]]
	2 arguments : the url & the config object
### POST REQUEST : 
![[screenshot-www.udemy.com-2023.08.06-18_05_09.png]]
	3 arguments : url + body (the url-encoded request we receive from the form containing password and username for example) + config object

### PUT REQUEST : ![[screenshot-www.udemy.com-2023.08.06-18_10_07 1.png]]
	 3 arguments : url + body (the url-encoded request we receive from the form containing password and username for example) + config object


### PATCH REQUEST (reminder: = put request but don't gotta replace all of the values) :
SAME AS PUT BUT WITH .PATCH

### DELETE REQUEST 
SAME AS GET BUT WITH .DELETE