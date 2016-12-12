# Lykuid Agent

This template deploys a [Lykuid](https://www.lykuid.com/) agent stack consisting of the official [docker-lykuid-agent](https://www.github.com/loopingz/docker-lykuid-agent) image and a configuration sidekick that provides closer integration with Rancher:

It is based on the Datadog agent configuration
* Hosts in Datadog are named correctly
* Host labels can be exported as DataDog host tags
* Service labels can be exported as DataDog metric tags
