api doc

http://localhost:8000/api/register  -> post

request

{
    "name":"antony",
    "email":"anto@gmail.com",
    "password":"12345678",
    "c_password":"12345678"
}

response

{
    "token": "1|sKVVXNZluOmA6A9yGdFJ7R",
    "name": "antony"
}


http://localhost:8000/api/login  -> post

request

{
    "email":"anto@gmail.com",
    "password":"12345678"
}

response

{
    "token": "2|1eqqvJgg5hEab5HRldtU20fd3",
    "name": "antony"
}

http://localhost:8000/api/detail  -> get

response

{
    "user": {
        "name": "antony",
        "email": "anto@gmail.com"
    }
}