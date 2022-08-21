## Dockerize NextJs Application on Github Pages through Github Action With Dockerize development Hot reloading

### Dockerize development Hot reloading

1. Init without install nodeJs and nextJs. Necessary files contain `Dockerfile.local` and `next.config.js`.
1. [Hot reloading Next.js with Docker in development](https://jameschambers.co.uk/nextjs-hot-reload-docker-development) with Dockerfile and next.config.js
1. Run the image: `docker-compose up -d --build`.

### Dockerize NextJs Application on Github Pages through Github Action

1. Necessary files contain `Dockerfile` and `.github/workflows/master.yml`. Also package.json need to add `"build": "next build && next export"` and `"homepage": "{{url}}",`.
