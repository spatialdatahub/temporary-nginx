# temporary-nginx
Displayed at spatialdatahub.org while we move from amazon web services to local servers

To use this, first build the docker file 
docker build . -t temporary-nginx

Then run it with
docker run --name temp -p 80:80 temporary-nginx
