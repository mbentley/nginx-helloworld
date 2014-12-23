mbentley/nginx-helloworld
==========================

Basic Hello World website to show build processes and CI with Jenkins as a quick example w/nginx to serve static HTML.

## Quick Steps
 - Edit `index.html`
 - Build a new Docker image: `docker build --rm -t mbentley/nginx-helloworld .`
 - Run the container: `docker run -itd -p 80:80 mbentley/nginx-helloworld`
