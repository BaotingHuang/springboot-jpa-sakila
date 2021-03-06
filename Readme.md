# Spring Boot JPA 
A Spring Cloud Docker - Kubernetes Example

## Built With

* [SpringBoot](https://spring.io/projects/spring-boot) - The framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [Docker](https://www.docker.com/) - Used containerise the application
* [Kubernetes](https://kubernetes.io/) - Used to generate a scalable cloud microservice
* [DB Documentation](https://www.ntu.edu.sg/home/ehchua/programming/sql/sampledatabases.html) - MySQL's Sample Salika (DVD Rental) Database


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
Give examples
```

### Installing

<code> kubectl apply -f springboot-jpa.yaml </code>

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why


* [Actors](http://localhost:31449/actors) - http://localhost:{port}/actors
* [Films](http://localhost:31449/film) - http://localhost:{port}/film
* [Actorinfo](http://localhost:31449/actorinfo) - http://localhost:{port}/actorinfo
* [Custom Query](http://localhost:31449/actorinfo/search/findByActorsLastName?name=GUINESS) - http://localhost:{port}/actorinfo/search/findByActorsLastName?name=GUINESS

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system


## Versioning

I use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/aballaci/springboot-jpa-sakila/tags). 

## Authors

* **Armand Ballaci** 

## License

This project is licensed under the MIT License - see the [LICENSE.md](Licence.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
