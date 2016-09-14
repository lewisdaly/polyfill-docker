
#to build
docker build -t polyfill .

# to run
docker run -dit  -p 8080:3000 --name polyfill polyfill

#go to:
http://docker.local:8080/v2/polyfill.min.js

#cleanup
docker rm -f -v polyfill
