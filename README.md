# Lelylan Nodes

Enable a two way communication between the cloud and the physical world
(a node enable the communication between Lelylan and a specific protocol/product)

#### Supported Nodes

- [x] MQTT

#### Desired Nodes

We want to connect as many existing connected products using different Lelylan Nodes. A nice project heading to this direction is [thethingsystem](http://thethingsystem.com/dev/supported-things.html).


## Requirements

Lelylan Nodes is tested against Node 0.8.8.


## Installation

    $ npm install && npm install -g foreman
    $ nf start

When installing the service in production set [lelylan environment variables].


## Resources

* [Lelylan Physical API]


## Contributing

Fork the repo on github and send a pull requests with topic branches.
Do not forget to provide specs to your contribution.


### Running specs

        npm install
        npm test


## Coding guidelines

Follow [Felix](http://nodeguide.com/style.html) guidelines.


## License

Lelylan is licensed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).
