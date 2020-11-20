# nodejs-example

run nodejs:
node hello.js


build docker image:
docker build -t  nodex .

run nodejs aplication in docker:
docker run -p 49160:3000  nodex


run with env variables:
docker run -p 49160:3000 -e var=var nodex

