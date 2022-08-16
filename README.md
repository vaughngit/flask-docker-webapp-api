# flask-docker

# Prereqs:
    python3: https://www.python.org/downloads/
    Docker: https://www.docker.com/products/docker-desktop/ 
    

# How to test locally: 

## build the image
docker build -t flask-webapi .

## run the container
docker run -d -p 5000:5000 --rm --name python-webapi flask-webapi 

## confirm container running
docker ps

## view logs
docker logs python-webapi

# view app webage: 
    http://http://localhost:5000/ 

## kill/stop container
docker stop python-webapi


### Resources: 
    Faker documentation: https://faker.readthedocs.io/en/master/ 
    Flask Docker Template: https://github.com/olu-damilare/flask-docker 