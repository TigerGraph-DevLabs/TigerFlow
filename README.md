# TigerFlow

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)         [![Docker Status](https://img.shields.io/docker/pulls/graphflow/tigerflow.svg)]()


TigerFlow is a flow chart visual programming language that it is based on Node-Red that comes preconfigured with TigerGraph Storage Nodes.
The TigerFlow runtime is lightweight and built on top of Node.js. It takes full advantage of Node.js’ event-driven, non-blocking I/O model. There is also the added benefit of tapping into the most used programming language — JavaScript!

## Features :rocket:

- Run standard GSQL Queries
- Upsert vertices to the Graph
- Upsert edges to the graph
- Run queries 
- TigerFlow can accept multi sources and act against multi graphs and multi servers


## Tech :rocket:

TigerFlow uses a number of open source projects to work properly:
- [Node-red] - the core on which TigerFlow is based 
- [AngularJS] - HTML enhanced for web apps!
- [Ace Editor] - awesome web-based text editor
- [node.js] - evented I/O for the backend
- [Express] - fast node.js network app framework [@tjholowaychuk]
- [jQuery] - duh

## Installation :rocket:

The TigerFlow can be ran via docker you will need to have docker installed.

pull a local docker image of TigerFlow

```sh
docker pull 
```

Run the container ...

```sh
docker run -it -p 1880:1880 -v ~/tigerflow-data:/data --name myTigerGraphPipeLine graphflow/tigerflow
```

> Note: ` ~/tigerflow-data` is the folder used for persistent data.

Verify the deployment by navigating to your server address in
your preferred browser.

```sh
http://127.0.0.1:1880
```

## Tutorial

Needed information to get up and running

| Type | Value |
| ------ | ------ |
| flow | https://raw.githubusercontent.com/zrougamed/medium/main/flows.json |
| Server | ip address our <host>.i.tgcloud.io |
| Port | the RESTPP Port (default : 9000) |
| User | the tigergraph username |
| Password | the tigergraph password |
| Secret | the graph secret |

## Video


## License

Apache 2.0
