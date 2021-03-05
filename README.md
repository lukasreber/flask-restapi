# flask-restapi

# start flask app
python api.py

# simple GET request
curl http://127.0.0.1:5000/multi/10

# simple POST request
curl -H "Content-Type: application/json" -X POST -d '{"name":"xyz","address":"address xyz"}'  http://127.0.0.1:5000/