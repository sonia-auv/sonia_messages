# SONIA MESSAGES

SONIA'S custom ROS messages package, containing all custom messages developed to work along with our custom ROS modules

![Docker Image CI - Master Branch](https://github.com/sonia-auv/sonia_messages/workflows/Docker%20Image%20CI%20-%20Master%20Branch/badge.svg)
![Docker Image CI - Develop Branch](https://github.com/sonia-auv/sonia_messages/workflows/Docker%20Image%20CI%20-%20Develop%20Branch/badge.svg?branch=develop)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/sonia-auv/sonia_messages)
![Average time to resolve an issue](https://isitmaintained.com/badge/resolution/sonia-auv/sonia_messages.svg)


## Getting Started


Project can be cloned locally as an individual package, it can be done using the following command:

```bash
git clone git@github.com:sonia-auv/sonia_messages.git
```

It is also possible to install the whole AUV-environment using the [auv-env-setup](https://github.com/sonia-auv/auv-env-setup) package

Finally a third option will be soon available using our custom CLI, further instruction will be provided at [sonia-cli](https://github.com/sonia-auv/sonia-cli)

### Prerequisites

To be able to use this project, you must install **docker** and **docker-compose**

Here are two recommended tutorials from Digital Ocean:

* To install docker see [Docker Install Ubuntu 18.04](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-18-04)
* To install docker-compose see [Docker Compose Install Ubuntu 18.04](https://www.digitalocean.com/community/tutorials/how-to-install-docker-compose-on-ubuntu-18-04)


### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Test can be run locally using the following commands:

```bash
catkin_make run_tests
catkin_make tests
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

The following packages are examples they should be replaced with project dependencies

* [ROS](http://wiki.ros.org/) - ROS Framework
* [Docker](https://docs.docker.com/) - Docker

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [Release Page](https://github.com/sonia-auv/sonia_msgs/releases).

## License

This project is licensed under the GNU License - see the [LICENSE](LICENSE) file for details
