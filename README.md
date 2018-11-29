# Automation Testing for API

In this project we use:
- Postman
- Newman
- Javascipt

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software and how to install them

```
NodeJS
Postman
Newman
Git
```

After install you should clonse repostory

```
git clone git@github.com:luizlohn/neon-api-automation-test.git
```

### Installing

To run, follow the steps: Go to project folder

First step, you need to install Newman running:

```
npm install newman
```


## Running the tests

To run

```
newman run Neon.postman_collection.json -e QA.postman_environment.json
```

- Neon.postman_collection.json --> Its a file with cenarious
- QA.postman_environment.json --> Its a file with environment used on tests

### PlayList listened to do this project: ###
[Deezer Frank Sinatra](https://www.deezer.com/artist/617?utm_source=deezer&utm_content=artist-617&utm_term=1624798546_1543511563&utm_medium=web)

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/luizlohn/neon-api-automation-test/tags).

## Authors

* **Luiz Lohn** - [My Web Site](https://luizlohn.com.br)
My repositories [Github](https://github.com/luizlohn).
