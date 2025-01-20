# Introduction to CI/CD

Here are some thoughts on `Python` programming language from the points below to discuss.

> [!NOTE]
> However, it is a good idea to consider the project requirements, experience and skills of software developers when choosing tools for CI/CD development.

## Some common steps in a CI setup include linting, testing, and building. What are the specific tools for taking care of these steps in the ecosystem of the language you picked?

### Linting

`Pylint` seems to be a good choice due to its popularity, configurability, versatility, ability to build Jenkins CI/CD pipelines, and Visual Studio Code extension.

**Pros:**
* Easy to install, analyse and orchestra
* Follows standard coding practises in error detection
* Checks both committed and uncommitted code

**Cons:**
* Sometimes shorten the code length breaking the code and meaning of the code changes
* Attempts to force a specific coding style

Sources: [10 Python Linter Platforms to Clean Up Your Code](https://geekflare.com/dev/python-linter-platforms/), [Linting Python in Visual Studio Code](https://code.visualstudio.com/docs/python/linting), [What is Pylint? Python Programming Tool](https://ipwithease.com/what-is-pylint-python-programming-tool/)

### Testing

There is three main part in testing:
* Unit testing
* Unit test coverage
* Integration testing

Python `unittest` module seems to be good, simple and well documented for unit testing.

It can also produce unit test coverage report to command line result or even to HTML format. This helps to cover the scope of unit tests. 

It can also be used to create integration tests. 

Source: [Python Unit Testing](https://www.pythontutorial.net/python-unit-testing/)

### Building

`PyBuilder` would be a good choice due to its simplicity and extensibility. It allows developers to maintain organized, efficient, and repeatable project pipelines.

Source: [Best 15 Python Build Tools For 2024](https://www.lambdatest.com/blog/python-build-tools/)

## What alternatives are there to set up the CI besides Jenkins and GitHub Actions?

There are many alternatives to set up the CI:
* GitLab CI
* Spacelift
* CircleCI
* Travis CI
* CodeShip
* AWS CodePipeline
* Azure DevOps
* Bitbucket Pipelines
* TeamCity


Source: [Top 10 Most Popular Jenkins Alternatives for DevOps in 2025](https://spacelift.io/blog/jenkins-alternatives)

## Would this setup be better in a self-hosted or a cloud-based environment? Why? What information would you need to make that decision?

It depends on many things, such as:
* Budget
* Requirements
* Skills
* Network capasity
* Data security
* Size and type of project

This depends totally on situation and without more detailed information, this cannot be answered.

The most likely option is a hosted service without your own hardware.

Comparison between different services is below.

### On Premise

**Pros:**
* Complete control over IT infrastructure
* Customizable to meet needs
* Lower long-term costs and no subscription fees

**Cons:**
* High upfront and maintenance costs
* Greater potential for data loss 
* Needs hands-on IT staff involvement

### Cloud

**Pros:**
* Enhanced security and data protection
* No large capital investment
* Lower maintenance costs
* Geographic redundancy
* Scalable

**Cons:**
* No control over the server hardware 
* Potential compliance challenges 
* Danger of vendor lock-in

### Hosted

**Pros:**
* Budget-friendly pricing model 
* Little to no maintenance is needed 
* Variety of services to choose from 
* Can be accessed from anywhere 
* Scalability, flexibility, security

**Cons:**
* Danger of vendor lock-in
* Loss of control
* Limited customization

Source: [Hosted vs Cloud vs On Premise Services](https://tealtech.com/blog/hosted-vs-cloud-vs-on-premise/)
