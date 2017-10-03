# dockerapp
A sample docker container to host a python web application

### step 1: Clone github repo 
```bash
git clone git@github.com:vishwambhar/dockerapp.git
``` 

### step 2: Build web application docker image from Dockerfile
```bash
docker build -t dockerapp:v0.1 .
```

### step 3: Pull image identifier of new built 'dockerapp' image
```bash
docker images
```

### step 4: Start docker container
```bash
docker run -it -p 5000:5000 833446b0a258
```

### step 5: Access the web application from a local web browser

