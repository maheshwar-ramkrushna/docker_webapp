# docker_webapp


#go to app folder

cd /path/to/app


# build image name as getting-started

docker build -t getting-started .


# start docker container

docker run -dp 3000:3000 getting-started


#access the url , if u r executing on dgx machine

http://<d_ip>:3000
