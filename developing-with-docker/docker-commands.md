docker run -d -p 8081:8081 -e ME_CONFIG_MONGODB_ADMINUSERNAME=admin -e ME_CONFIG_MONGODB_ADMINPASSWORD=password --net mongo-network --name mongoExpress -e ME_CONFIG_MONGODB_SERVER=mongo_DB mongo-express

