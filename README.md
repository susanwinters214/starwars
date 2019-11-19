# starwars
(Project from ZTM. Section 22)

This project will use the StarWars API located at: swapi.co.
Base URL Location: https://swapi.co/api/
API Documentation: https://swapi.co/documentation
JSON Schema: Making a request to /api/<resource>/schema will give you the details of that resource.

Example response:

HTTP/1.0 200 OK
Content-Type: application/json
{
    "films": "https://swapi.co/api/films/",
    "people": "https://swapi.co/api/people/",
    "planets": "https://swapi.co/api/planets/",
    "species": "https://swapi.co/api/species/",
    "starships": "https://swapi.co/api/starships/",
    "vehicles": "https://swapi.co/api/vehicles/"
}

This API project will concentrate on PEOPLE in StarWars.
http https://swapi.co/api/people/1/
