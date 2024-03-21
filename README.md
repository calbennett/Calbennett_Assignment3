# Calbennett_Assignment3

## 1. Find movies from 1983 with runtime over 200 minutes.
db.movies.find({"year":1983, "runtime":{$gt:200}}, {"title":1, "year":1, "runtime":1, "_id":0})
![alt text](https://github.com/calbennett/Calbennett_Assignment3/blob/main/A3%20Question%201.PNG)

## 2. Find movies from after 2014 with an IMDB rating over 9
db.movies.find({"year":{$gt:2014}, "imdb.rating":{$gt:9}}, {"title":1, "year":1, "imdb.rating":1, "_id":0}
![alt text](https://github.com/calbennett/Calbennett_Assignment3/blob/main/A3Question2.PNG)
