# MovieTickets Backend

Backend built from scratch with easy tutorial using Node, Express and Mongoose.

Before your start the server, you need to install MongoDB:

1. Install MongoDB

```
brew install mongodb
```

2. create dir for database
```
mkdir -p /data/db
```

3. Set your permission 
```
sudo chmod 777 /data/db
```

4. Finally launch your MongoDB
```
mongod&
```
if there's an error, try using this

```
sudo mongod
```

You can manage your database with [Robo 3T](https://robomongo.org/).

after you have launched and connected to MongoDB, you can clone this repo

```
git clone https://github.com/irhamputra/MovieTickets-Backend
cd MovieTicketBackend
npm install
npm start
```

That's it! you have started the server and you can listen from localhost:3000.

> To see Movies.json package just type in your browser localhost:3000/v1/movies.json