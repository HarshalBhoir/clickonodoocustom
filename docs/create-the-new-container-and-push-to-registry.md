# Create the New Container and push to registry

## Log into your DockerHub account

In your security settings create a new access token and follow the instructions to login

Alternatively use the standard login procedure for dockerhub cli

```text

```

Once logged in,

## Commit the changes to create a new container with your customisation finished

```text
docker commit <imagename> <newimagename>:latest
```

or to publish a new container using the existing modified container to 

## dockerhub:

### Tag the  new image

```text
docker tag <imagename>:latest <username>/<newimagename>:latest<:or-tag>
```

### Push

```text
docker push <username><newimagename>:latest
```

You can now test your new image

