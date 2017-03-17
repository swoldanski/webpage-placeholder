# Webpage placeholder container for Docker
Quick How-to

1. git clone https://github.com/swoldanski/webpage-placeholder.git

2. add your files to **src** folder

3. build your new container:
**docker build . --tag your-username/container-name-for-docker-hub**

4. push container to docker hub:
**docker push your-username/container-name-for-docker-hub**

5. use it :D

for quick test your new webpage placeholder use **docker run -it -p 80:80 your-username/container-name-for-docker-hub** and open (http://localhost)
