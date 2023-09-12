# Multi Stage Docker build example
`Dockerfile` contains various stages which are tagged by a name using `as`.

## Commands used
- `docker build . -t multi-stage-example:v1` - Build image
- `docker build . -t multi-stage-example:v1 --target=builder` - Build image using a specific stage
- `docker run  -p 8080:8080 multi-stage-example:v1` - Run image
