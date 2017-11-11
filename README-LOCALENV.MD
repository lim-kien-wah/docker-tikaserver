
#To start VM hosting the Tika server
docker-machine start default

#To start Tika server application
docker run -d -p 9998:9998 logicalspark/tikaserver

docker-machine stop
