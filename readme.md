
docker build -t castle-demo-python .

docker run -d -p 4005:80 -e castle_app_id=352958777265693 -e castle_api_secret=GZsCzr3eXhpc4Qbw6xuWWMzfSDLrUZCx castle-demo-python