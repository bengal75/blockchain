# Learn Blockchains by Building One

This is the source code for Daniel van Flymen's post on [Building a Blockchain](https://medium.com/p/117428612f46).

Adapted by [Ben Galloway](mailto:ben@bengalloway.io) for use at UAE Cyber Quest 2018.

## Example Use in Docker

One option for running this blockchain program is to use Docker. Follow the instructions below to create a local Docker container:

1. Clone this repository
2. Build the Docker container

```
$ docker build -t blockchain .
```

3. Run the container

```
$ docker run --rm -p 80:5000 blockchain
```

4. To add more instances, vary the public port number before the colon:

```
$ docker run --rm -p 81:5000 blockchain
$ docker run --rm -p 82:5000 blockchain
$ docker run --rm -p 83:5000 blockchain
```
