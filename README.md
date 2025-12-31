# ubi-dev
images used for development enviroment



## with docker build (in git bash)
~~~
docker build --progress plain -f Dockerfile_UBI93 --progress plain -t devopsteamelt/dev_image_ubi93:v1.0.0 . 2>&1 |  tee res.txt
docker push devopsteamelt/dev_image:v1.0.0
~~~