# go_rest_api_v1

Implementation of a REST API with golang, based on the example from http://thenewstack.io/make-a-restful-json-api-go/


### POST example

curl -H "Content-Type: application/json" -d '{"name":"New Todo"}' http://localhost:8080/todos
Now, if you go to http://localhost/todos we should see the following response:

    [
        {
            "id": 1,
            "name": "Write presentation",
            "completed": false,
            "due": "0001-01-01T00:00:00Z"
        },
        {
            "id": 2,
            "name": "Host meetup",
            "completed": false,
            "due": "0001-01-01T00:00:00Z"
        },
        {
            "id": 3,
            "name": "New Todo",
            "completed": false,
            "due": "0001-01-01T00:00:00Z"
        }
    ]