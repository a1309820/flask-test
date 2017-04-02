followed tutorial from:
https://blog.miguelgrinberg.com/post/designing-a-restful-api-with-python-and-flask

start python job with:
python app.py

example curl calls:
curl -i http://localhost:5000/todo/api/v1.0/tasks

curl -l http://localhost:5000/todo/api/v1.0/tasks/2

curl -i -H "Content-Type: application/json" -X PUT -d '{"done":true}' http://localhost:5000/todo/api/v1.0/tasks/2

curl -i -H "Content-Type: application/json" -X POST -d '{"title":"Read a book", "description":"Reading is good"}' http://localhost:5000/todo/api/v1.0/tasks


