mbentley/nginx-helloworld
==========================

Basic Hello World website to show build processes as a quick example w/nginx.

## Quick Steps
 - Edit `index.html`
 - Build a new Docker image: `docker build --rm -t mbentley/nginx-helloworld .`
 - Run the container: `docker run -itd -p 80:80 mbentley/nginx-helloworld`
