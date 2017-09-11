
# Getting started

Pixi is a multi-container Docker application; there's a NodeJS application
container and a MongDB database container.

The application is defined in the `docker-compose.yaml` file; to run it,
make sure you have `docker-compose` installed
([instructions](https://docs.docker.com/compose/install/)) and then run:

```
docker-compose up
```

This will expose the following ports:

* 8000: Pixi web UI, accessible at http://localhost:8000/
* 8090: Pixi API, accessible at http://localhost:8090/
* 27017: MongoDB native interface
* 28017: MongoDB HTTP interface, http://localhost:28017/

As a new user, after running `docker-compose up`, you can open your browser to the Pixi web UI and use the **Register Here!** button to set up a new account. You don't need to provide your real email address, you can use `test@example.com` or something else if you want.

Once you're logged in, Pixi will give you more instructions.

Have fun!