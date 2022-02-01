# Docker Hello World - All in one

This is a presentation version of my [docker hello
world](https://github.com/SonkeWohler/docker_yaml).  It clones all projects
involved so you can better inspect them, but otherwise simply represents the
docker-compose part of it (i.e. a single yaml file).

## Cloning

Simply run the following:

```
git clone --recursive git@github.com:SonkeWohler/docker_present.git
```

## Running

Then you should be able to run via `docker-compose up`.  If you are on Windows
this may fail due to symlinks, simply go to the [`docker_yaml`](./docker_yaml)
project and run from there.

The output will be at [`localhost:8080`](http://localhost:8080).

You can inspect the backend output at [`127.0.0.1:5000/hello`](http://127.0.0.1:5000/hello).
