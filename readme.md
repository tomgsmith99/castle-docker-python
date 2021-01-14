
docker build -t castle-demo-python .

docker run -d -p 4005:80 -e castle_app_id={{castle_app_id} -e castle_api_secret={{castle_api_secret}} castle-demo-python