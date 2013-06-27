# MQTT server for Lelylan

MQTT server for Lelylan [Lelylan](http://dev.lelylan.com)


## Requirements

The Realtime service is tested against Node 0.8.8.


## Installation

Clone the repository.

    git clone git@github.com:lelylan/mqtt.git

Run Node server.

    foreman start


## Getting Started

[Express server](http://localhost:8004)
[MQTT server](http://localhost:1883)

## Deploy

Follow [Node.js on Heroku](https://devcenter.heroku.com/articles/nodejs).


## Resources

* [Mosca](https://github.com/mcollina/mosca) and
* [Ascoltatori](https://github.com/mcollina/ascoltatori).
* [Physical API](http://dev.lelylan.com/api/physicals)


## Contributing

Fork the repo on github and send a pull requests with topic branches.
Do not forget to provide specs to your contribution.

### Running specs

* Fork and clone the repository
* Run `gem install foreman`
* Run `npm install`
* Run `foreman start --env .test.env` (`.test.env` contains the database test URIs)
* Run `foreman run mocha spec/app.spec.js --env .test.env`


## Coding guidelines

Follow [github](https://github.com/styleguide/) guidelines.


## Feedback

Use the [issue tracker](http://github.com/lelylan/mqtt/issues) for bugs.
[Mail](mailto:touch@lelylan.com) or [Tweet](http://twitter.com/lelylan) us for any idea that can improve the project.


## Links

* [GIT Repository](http://github.com/lelylan/mqtt)
* [Mosca](https://github.com/mcollina/mosca)
* [Ascoltatori](https://github.com/mcollina/ascoltatori)
* [Physical API](http://dev.lelylan.com/api/physicals)
* [Lelylan Dev Center](http://dev.lelylan.com)
* [Lelylan Site](http://lelylan.com)


## Authors

[Andrea Reginato](http://twitter.com/andreareginato)


## Contributors

Special thanks to the [following people](https://github.com/lelylan/mqtt/contributors) for submitting patches.


## Changelog

See [CHANGELOG](mqtt/blob/master/CHANGELOG.md)


## Copyright

Copyright (c) 2013 [Lelylan](http://lelylan.com).
See [LICENSE](mqtt/blob/master/LICENSE.md) for details.