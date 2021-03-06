# Composed Docker Deployment

## Introduction

Use this blueprint to deploy a simple Docker application to Docker running locally.

## Before you get started

If you're new to XebiaLabs blueprints, check out:

* [Get started with DevOps as Code](https://docs.xebialabs.com/xl-release/concept/get-started-with-devops-as-code.html)
* [Get started with blueprints](https://docs.xebialabs.com/xl-release/concept/get-started-with-blueprints.html)

## Prerequisites

* XebiaLabs Deployment Automation up and running
* A local Docker installation up and running

## Usage

To use this blueprint, run `xl blueprint` in an empty directory and select:

```plain
docker/composable-demo
```

## Tools and technologies

This blueprint includes the following tools and technologies:

* Target:
  * [Docker](https://www.docker.com/)
* Tools:
  * [XebiaLabs Deployment Automation](https://xebialabs.com/products/xl-deploy/)

## Minimum required versions

This blueprint version requires at least the following versions of the specified tools to work properly:

* XL Deploy: Version 9.0
* XL CLI: Version 9.0

## Information required

* The application name
* The port where the application should be exposed
* Docker image for a front-end service
* The URL for your Docker engine

## Output

* Docker infrastructure
* Docker application definition

## Labels

* Docker

