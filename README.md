# papyri

Papyri is a tool to fetch, manage and own your data.

The idea for the name `Papyri` comes from the _Villa of Papyri_ in the ancient Roman city of Herculean in present-day southern Italy, which had a fabled library with a world-class collection of _papyri_, or scrolls, of great knowledge.   

## Technical Overview 

It is a monorepo, consisting of API and UI microservices.

The API is a Micronaut, Java, and Gradle microservice, and the UI is a very stripped-down React app.

It is written using functional reactive programming (FRP) using Java, Vavr, RxJava and JavaScript, and RxJs.

It is deployable onto a standalone Linux server with Docker (JVM, Nginx containers), or a Kubernetes. It includes a development environment using Kubernetes as well.

## Getting Started 

1. Clone this repo and `cd papyri`.

1. Install Java ([Install SDKMan](https://sdkman.io/install) then run `sdk install java`)

### Start the API

1. `cd api`
1. Build and run: `./gradlew build run`

### Start the UI

1. Navigate to the `ui-pure/index.html` file

## Deployment 

The plan is to use Kubernetes to closely mirror the development environment from production (within reason!). For now, NGINX on a Linux box will be used.

A GitOps-style setup with ArgoCD will be evaluated for Kubernetes.  

# Contributing

//todo

## Development Norms

//todo

# Code of Conduct

//todo

# Reference

## Built using 
- Micronaut
- Bare-bones React


### React Documentation

- [Learning React, 2nd Edition](https://learning.oreilly.com/library/view/learning-react-2nd/9781492051718/ch01.html)
- [Docs](https://reactjs.org/docs/)

### Micronaut 2.4.0 Documentation

- [User Guide](https://docs.micronaut.io/2.4.0/guide/index.html)
- [API Reference](https://docs.micronaut.io/2.4.0/api/index.html)
- [Configuration Reference](https://docs.micronaut.io/2.4.0/guide/configurationreference.html)
- [Micronaut Guides](https://guides.micronaut.io/index.html)
---

### Feature http-client documentation

- [Micronaut HTTP Client documentation](https://docs.micronaut.io/latest/guide/index.html#httpClient)

