### [&laquo; Home](README.md)

[Authentication for Suitbase API](#authentication-for-bukalapak-api)
- [Authenticate](#authenticate)
    - [URL](#url)
    - [Parameters](#parameters)
    - [Example Request](#example-request)
    - [Example Response](#example-response)

## Authentication for Suitbase API

### Authenticate
Return token to enable access for `required authentication's resources`
User Suitbase `user` and `password` for server authentication.

+ Use `POST` http method.

##### URL
+ [https://base.suitmedia.com/api/v1/login]()

##### Parameters
- username
- password

##### POST request data
None

##### Example Response
Success response:
````json
{
  "token": "U8Ch2LigkVhdI3XwYRA",
  "message": "Login Success!"
}
````

Failed response
Status code: 401
````json
{
  "message":"Bad Credentials!"
}
````
