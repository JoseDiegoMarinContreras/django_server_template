# django_server_template
---

## This a simple django app

### Run this server
`python .\manage.py runserver`

---

# TODO

## 1. Fix the server
Something is happening with the server, the server is trying to run on port 8080, but when making request to "/" we're getting a error.

## 2. Send the greetings from /greetings
Cool! you just fixed the server. Wait a second... ohhh no we aren't able to send response from /greetings route, fix the route to send the greetings.

## 3. Create more endpoints
Woow you are killing it, you already fix the server and we are sending greetings. Now we need to create more endpoints.
Using the API of [PokéAPI](https://pokeapi.co/) we need to create the following endpoint.
- /pokeapi
  + Get 10 pokemons
  + Sorted it
  + Fetch the data of url property

---
### Extra points
- Create a react app
`npx create-react-app --template=typescript`
- Display the pokemons in a list and when click on a pokemon show their details (url props)
---
