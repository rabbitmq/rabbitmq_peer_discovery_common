# RabbitMQ Peer Discovery Commons

## This was migrated to https://github.com/rabbitmq/rabbitmq-server

This repository has been moved to the main unified RabbitMQ "monorepo", including all open issues. You can find the source under [/deps/rabbitmq_peer_discovery_common](https://github.com/rabbitmq/rabbitmq-server/tree/master/deps/rabbitmq_peer_discovery_common).
All issues have been transferred.

## Introduction

This library is similar in purpose to [rabbit-common](https://github.com/rabbitmq/rabbitmq-common) but focusses exclusively
on [RabbitMQ peer discovery backends](https://www.rabbitmq.com/cluster-formation.html) (available as [a plugin](https://github.com/rabbitmq/rabbitmq-autocluster) for 3.6.x releases).

It is not supposed to be enabled, disabled or used directly by the users, only as a
dependency of other plugins.


## Project Maturity

This library [shipped with RabbitMQ 3.7.0](https://github.com/rabbitmq/rabbitmq-server/releases/tag/v3.7.0).


## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md) and our [development process overview](https://www.rabbitmq.com/github.html).


## License

[Licensed under the MPL](LICENSE-MPL-RabbitMQ), same as RabbitMQ server.


## Copyright

(c) 2007-2020 VMware, Inc. or its affiliates.
