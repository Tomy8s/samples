# Node.js Sample App using NPM

## Building

### Using base builder

`pack build npm-sample --buildpack paketo-buildpacks/nodejs --builder paketobuildpacks/builder:base`

### Using full builder

`pack build npm-sample --buildpack paketo-buildpacks/nodejs --builder paketobuildpacks/builder:full`

## Running

`docker run --init --publish 8080:8080 npm-sample`

## Viewing

`curl http://localhost:8080`
