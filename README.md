Up DBs `docker-compose up`

`cd admin`
`tsc -w`
run `npm start`


`cd ../main`
`tsc -w`
run `npm start`

### RabbitMQ
http://localhost:15672/
guest/guest


### MondbDB
#### install mongo
brew tap mongodb/brew && brew install mongodb-community-shell
mongo --version

#### connect to mongo db
mongo
show dbs
use yt_node_main
show collections
use product

##### data manipulation
db.product.find()
  { "_id" : ObjectId("6431a855d0179fe3c6c152ba"), "admin_id" : 2, "title" : "the first product", "image" : "the/new/url911", "likes" : 5 }

db.version()

