# Docker Hello World - All in one

This is a testing version of my [docker hello
world](https://github.com/SonkeWohler/docker_yaml).  It clones all projects
involved so you can better inspect them, but otherwise simply represents the
docker-compose part of it (i.e. a single yaml file).

## Cloning

Simply run the following:

```
git clone --recursive git@github.com:SonkeWohler/docker_present.git
```

## Running

Then you should be able to run via `docker-compose up`.

The output will be at [`localhost:8080`](http://localhost:8080).

You can inspect the backend output at [`127.0.0.1:5000/hello`](http://127.0.0.1:5000/hello).

If you make changes to the containers you may have to pass `--build` to
`docker-compose` or it may reuse the outdated images.
