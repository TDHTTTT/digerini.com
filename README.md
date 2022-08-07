# digerini.com 

The site is hosted on Cloudflare with Cloudflare pages.

## Develop Locally

Update 08/06/2022:

Gatsby.js doesn't support node:12 anymore so I pushed my working image to tdhttt/digerini-website:1.0. To use the image, simply run `docker pull tdhttt/digerini-website:1.0 && docker run tdhttt/digerini-website:1.0` 

To install all the node packages, run the gatsby dev docker with node as the user:

`docker run -it -v $PWD:/app dev-gatsby`

To develop it locally:

`docker-compose up`
