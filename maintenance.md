# drt-sdk-playground - maintenance

Skip this if you are not a maintainer of the Playground.

Build the Docker image:

```
docker build --network=host ./.devcontainer -t dharitri/development-playground:latest -f ./.devcontainer/Dockerfile
```

Push the Docker image:

```
docker push dharitri/development-playground:latest
```

Test the devcontainer by running the Visual Studio command:

```
Dev Containers: Rebuild and Reopen in Container
```
