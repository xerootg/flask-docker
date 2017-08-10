# Basic flask based hello world in docker

To build, `docker build -t flask-hello .`

The flask app is running on port 80

After building, it can be run by `docker run -d -p 80:80 flask-hello`

This will allow you to simply browse `localhost` and see the hello world.
