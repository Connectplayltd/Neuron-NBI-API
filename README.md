# Neuron NBi API

Neuron API is built based around OpenAPI Version 3.0 standard.

## Introduction to OpenAPI

<https://www.openapis.org>

The OpenAPI Specification (OAS) defines a standard, language-agnostic interface to RESTful APIs which allows both humans and computers to discover and understand the capabilities of the service without access to source code, documentation, or through network traffic inspection. When properly defined, a consumer can understand and interact with the remote service with a minimal amount of implementation logic.

An OpenAPI definition can then be used by documentation generation tools to display the API, code generation tools to generate servers and clients in various programming languages, testing tools, and many other use cases.

## Quick start

<https://app.swaggerhub.com/apis/Connectpla/NeuronNBI-PUB/1.0.0> , the API is already documented and hosted Swagger Hub.

You can start testing towards the Neuron platform hosted @ neuron.nz or acs.neuron.nz given you have the correct credentials to authenticate.

## Getting started with Swagger Hub

Sign up to Swagger and Creat a new API project.

<https://swagger.io>

* OepnAPI Version = 3.0.0
* Template = --NONE--
* Visibility = Private/Public
* Owner = Owner
* Auto Mock API = ON

Import the swagger.json file into Swagger Hub to generate the documentation and testing suite for Neuron API.

When prompted, convert JSON to YAML.

Swagger can also export API into a client SDK to generate mock source code for the developer.

If the platform is installed on-premises, the URL must be updated to reflect the hosted FQDN.

```
https://<FQDN/>IP>/V1/api/...
```

## Version

OpenAPI Version 3.

## Maintained

By Neuron DevOps. <devops@neuron.nz>

## Issues

Open an issue or get in contact with the Neuron devops team.