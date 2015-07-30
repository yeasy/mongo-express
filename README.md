mongo-express
===

# Supported tags and respective Dockerfile links

* [`latest` (latest/Dockerfile)](https://github.com/yeasy/mongo-express/blob/master/Dockerfile)

For more information about this image and its history, please see the relevant manifest file in the [`yeasy/mongo-express` GitHub repo](https://github.com/yeasy/mongo-express).

# What is mongo-express?
[mongo-express](https://github.com/andzdroid/mongo-express) is a web-based MongoDB admin interface, written with Node.js and express.

This project is based on [knickers/mongo-express](https://github.com/knickers/mongo-express), and has some customized changes.

# How to use this image?
The docker image is auto built at [https://registry.hub.docker.com/u/yeasy/mongo-express/](https://registry.hub.docker.com/u/yeasy/mongo-express/).


## In Dockerfile
```sh
FROM yeasy/mongo-express:latest
```

## Local Run
```sh
$ docker run --rm -it --env mongo=mongo_server_IP yeasy/mongo-express:latest
```

# Which image is based on?
The image is based on node:0.12-slim.

# What has been changed?
Install useful tools such as vim and git.

Use the latest mongo_express.


# Supported Docker versions

This image is officially supported on Docker version 1.7.1.

Support for older versions (down to 1.0) is provided on a best-effort basis.

# User Feedback
## Documentation
Be sure to familiarize yourself with the [repository's `README.md`](https://github.com/yeasy/mongo-express/blob/master/README.md) file before attempting a pull request.

## Issues
If you have any problems with or questions about this image, please contact us through a [GitHub issue](https://github.com/yeasy/mongo-express/issues).

You can also reach many of the official image maintainers via the email.

## Contributing

You are invited to contribute new features, fixes, or updates, large or small; we are always thrilled to receive pull requests, and do our best to process them as fast as we can.

Before you start to code, we recommend discussing your plans through a [GitHub issue](https://github.com/yeasy/mongo-express/issues), especially for more ambitious contributions. This gives other contributors a chance to point you in the right direction, give you feedback on your design, and help you find out if someone else is working on the same thing.

