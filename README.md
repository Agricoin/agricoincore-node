AgricoinCORE Node
============

A Agricoin full node for building applications and services with Node.js. A node is extensible and can be configured to run additional services.

## Install

```bash
npm install -g agricoincore-node
agricoincore-node start
```

## Configuration

AgricoinCORE includes a Command Line Interface (CLI) for managing, configuring and interfacing with your AgricoinCORE Node.

```bash
agricoincore-node create -d <data-dir> mynode
cd mynode
agricoincore-node install <service>
agricoincore-node install https://github.com/yourname/helloworld
```

This will create a directory with configuration files for your node and install the necessary dependencies. For more information about (and developing) services, please see the [Service Documentation](docs/services.md).

## Add-on Services

There are several add-on services available to extend the functionality of AgricoinCORE:

- [Agricoin Insight API](https://github.com/Agricoin/agricoin-api)
- [Agricoin Explorer](https://github.com/Agricoin/agricoin-explorer)

## Contributing



## License
