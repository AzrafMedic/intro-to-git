# Introduction to Platform Engineering at Gannett/USAToday Network

This introduction is meant to give people a starting point to learn all the infrastructure and processes currently in place in platform engineering. We will go into all the tools, documentation, links and access points needed to work with our current infrastructure as well as to understand processes that are still supported. 

## Getting Started

It is important to treat everything from the basic perspective that it is all code. We store all our infrastructure as code and we use our tools to package, test, and eventually deploy our applications. 

### List of all current tools and infrastructure

Here is a list of all of our current tools and infrastructure - as well as links to understand the tools more in-depth: 

#### Sprint Planning/Task Management

* JIRA

#### Code 

* Github
* Quay
* Artifactory
* Jenkins (CI/CD)

#### Deploy

* Docker / Kubernetes / Minikube
* Helm / Tiller
* GKE (Google Kubernetes Engine)
* Vault
* Google Load Balancer (GLB)

#### Monitor

* NewRelic
* VictorOps
* Sumologic

#### Delivery

* Apigee
* Fastly (Written in VCL - Varnish Configuration Language)
* Terraform
* Couchbase
* Google Pub/Sub

#### Still Supported Services

* RabbitMQ
* Scalr
* Chef

## An Overview of the Platform Stack

![alt text](


### Prerequisites

What things you need to install the software and how to install them

```
Give examples
```

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

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
