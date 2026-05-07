## MongoDB Setup

This project expects a local MongoDB instance running at:

mongodb://localhost:27017

Database name:

mongo_workshop

Required setup commands in mongosh:

```js
use mongo_workshop

db.example.insertOne({ x: 1 })

db.cars.insertOne({ make: "ford", model: "explorer", year: 2008 })
db.cars.insertOne({ make: "ford", model: "fiesta", year: 2012 })
db.cars.insertOne({ make: "honda", model: "civic", year: 2015 })
db.cars.insertOne({ make: "chevy", model: "impala", year: 1975, options: { radio: "8-track" } })
```

Run tests with:
```bash
npm test
```