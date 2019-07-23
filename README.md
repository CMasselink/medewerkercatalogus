<h1 align="center"><a href="https://common-ground.dev"><img src="https://common-ground.dev/logo-250x250.png" alt="Common Ground"></a></h1>

Welkom the the VNG Common Ground proto component!

This repository provides a plug and play solution for component generation on common ground. That means that it takes away all the husle of setting op codebases, containers and following the VNG Api Standaard. It does al that for you! 

For that we use **[Api Platform](https://api-platform.com)**, a next-generation web framework designed to easily create API-first projects without compromising extensibility
and flexibility. 

[![Build Status](https://travis-ci.org/api-platform/core.svg?branch=master)](https://travis-ci.org/api-platform/core)
[![Build status](https://ci.appveyor.com/api/projects/status/grwuyprts3wdqx5l?svg=true)](https://ci.appveyor.com/project/dunglas/dunglasapibundle)
[![codecov](https://codecov.io/gh/api-platform/core/branch/master/graph/badge.svg)](https://codecov.io/gh/api-platform/core)
[![SensioLabsInsight](https://insight.sensiolabs.com/projects/92d78899-946c-4282-89a3-ac92344f9a93/mini.png)](https://insight.sensiolabs.com/projects/92d78899-946c-4282-89a3-ac92344f9a93)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/api-platform/core/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/api-platform/core/?branch=master)

Features
-------
API Platform embraces open web standards (OpenAPI, JSON-LD, GraphQL, Hydra, HAL, JSONAPI, JWT, OAuth, HTTP...) and the [Linked Data](https://www.w3.org/standards/semanticweb/data) movement. Your API will automatically expose structured data in Schema.org/JSON-LD.
It means that your commonground application is usable **out of the box** with technologies of the semantic web.

* Comes with a paired [React](https://reactjs.org/) application, to provide face to your code
* And a fully functional (and automaticly updated) [React Admin](https://marmelab.com/react-admin/) backend to easly test and proof your component
* Design your own data model as plain old PHP classes or [**import an existing one**](https://api-platform.com/docs/schema-generator)
  from the [Schema.org](https://schema.org/) vocabulary
* **Expose in minutes a hypermedia REST or a GraphQL API** with pagination, data validation, access control, relation embedding,
  filters and error handling...
* Benefit from Content Negotiation: [GraphQL](http://graphql.org), [JSON-LD](http://json-ld.org), [Hydra](http://hydra-cg.com),
  [HAL](http://stateless.co/hal_specification.html), [JSONAPI](https://jsonapi.org/), [YAML](http://yaml.org/), [JSON](http://www.json.org/), [XML](https://www.w3.org/XML/) and [CSV](https://www.ietf.org/rfc/rfc4180.txt) are supported out of the box
* Enjoy the **beautiful automatically generated API documentation** (Swagger/[OpenAPI](https://www.openapis.org/))
* Add [**a convenient Material Design administration interface**](https://api-platform.com/docs/admin) built with [React](https://reactjs.org/)
  without writing a line of code
* **Scaffold fully functional Progressive-Web-Apps and mobile apps** built with [React](https://api-platform.com/docs/client-generator/react), [Vue.js](https://api-platform.com/docs/client-generator/vuejs) or [React Native](https://api-platform.com/docs/client-generator/react-native) thanks to [the client
  generator](https://api-platform.com/docs/client-generator) (a Vue.js generator is also available)
* Install a development environment and deploy your project in production using **[Docker](https://api-platform.com/docs/distribution#using-the-official-distribution-recommended)** and [Kubernetes](https://api-platform.com/docs/deployment/kubernetes)
* Easily add **[JSON Web Token](https://api-platform.com/docs/core/jwt) or [OAuth](https://oauth.net/) authentication**
* Create specs and tests with a **developer friendly API testing tool** on top of [Behat](http://behat.org/)
* use **thousands of Symfony bundles and React components** with API Platform
* reuse **all your Symfony and React skills**, benefit of the incredible amount of documentation available
* enjoy the popular [Doctrine ORM](http://www.doctrine-project.org/projects/orm.html) (used by default, but fully optional:
  you can use the data provider you want, including but not limited to MongoDB and ElasticSearch)

Getting started
-------

* Get your own commonent by simply forking this repository trough [generation](https://github.com/ConductionNL/commonground-component/generate).
* Pull a local copy of your repository trough your favorite git client (e.g [gitkraken](https://www.gitkraken.com/) or [sourcetree](https://www.sourcetreeapp.com/))
* Start up you local instance with [docker for desktop](https://hub.docker.com/?overlay=onboarding) and the $ docker-compose up command
* Open [http://localhost] in your favorite browser and view your component!

Credits
-------

Created by [Kévin Dunglas](https://dunglas.fr) and extended by [Ruben van der Linde](https://www.conduction.nl/team). Commercial support for commonground components available from [Conduction](https://www.conduction.nl).
