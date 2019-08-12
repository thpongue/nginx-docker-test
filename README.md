# prerequisites
Install docker
Install nginx

# nginx-docker-test
Example of docker and nginx working together to serve the contents of your dist folder on http://localhost:8080
For convenience I've turned the docker build and run commands into shell scripts.

# steps
1. build the image
```
./build.sh
```

2. run a container from the built image
```
./run.sh
```

3. exit when finished
ctrl+c 

To see any updates you've made inside the /dist folder go back to #1 and repeat the process

If you get permission denied then run the following:

```
chmod +x build.sh 
chmod +x run.sh 
```
