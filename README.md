# Awesome Asset Administration Shell (AAS)

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

We provide a curated list of awesome tools, platforms, libraries and documentation about Asset Administration Shell.
Items are listed alphabetically and do not follow a certain prioritization.

## Software Development Kits (SDKs) 🔨

SDKs provide the AAS meta-model for a certain programming language, *e.g.* as a class hierarchy.
On top of this, SDKs validate and de/serialize instances of the AAS.

### AAS4J
Java SDK, implements v3.0 of the spec.
Supports XML, JSON and AASX.

https://github.com/eclipse-aas4j/aas4j

### AAS Core C#
C# SDK.
Supports XML and JSON. Implements the following versions of the AAS meta-model:

* v3.0: https://github.com/aas-core-works/aas-core3.0-csharp
* v3.0RC02: https://github.com/aas-core-works/aas-core3.0rc02-csharp

### AAS Core Golang
Go SDK.
Supports XML and JSON.
Implements the following versions of the AAS meta-model:

* v3.0: https://github.com/aas-core-works/aas-core3.0-golang
* v3.0RC02: https://github.com/aas-core-works/aas-core3.0rc02-golang

### AAS Core Typescript
Typescript SDK.
Supports JSON.
Implements the following versions of the AAS meta-model:

* v3.0: https://github.com/aas-core-works/aas-core3.0-typescript
* v3.0RC02: https://github.com/aas-core-works/aas-core3.0rc02-typescript

### AAS Core Python
Python SDK.
Supports XML and JSON.
Implements the following versions of the AAS meta-model:

* v3.0: https://github.com/aas-core-works/aas-core3.0-python
* v3.0RC02 https://github.com/aas-core-works/aas-core3.0rc02-python

### BaSyx Python SDK
Python SDK, implements v2.0.1 of the spec.
Supports JSON, XML and AASX

https://github.com/eclipse-basyx/basyx-python-sdk

### BaSyx Rust SDK
Rust SDK, implements v3.0 of the spec.
Supports JSON.

https://github.com/eclipse-basyx/basyx-rust-sdk

## Server Frameworks 🖥
Server Frameworks enable the development of HTTP/REST interfaces to access an AAS.

### BaSyx Java V2 Server SDK

For Java, supports v3.0 of the AAS meta-model.

https://github.com/eclipse-basyx/basyx-java-server-sdk

## Tools 🔧

This sections lists end-user tools.

### AAS Core CLI Swiss Knife

Provide a set of command-line tools to:
* Convert CSV tables to AAS,
* Validate instances of AAS,
* Tree-shake concept descriptions,
* Check for dangling references, and
* Convert AAS to static file structures (in form of directories and JSON files) such that they can be statically served by a HTTP server (*e.g.* nginx) as a read-only AAS server.

Supports v3.0 of the AAS meta-model.

https://github.com/aas-core-works/aas-core3.0-cli-swiss-knife

### AAS Core React Editor
An editor of an AAS, implemented in React and TypeScript, which runs directly in the browser.

Contained as a single HTML file and needs no server or backend.

Supports v3.0RC02 of the meta-model.

https://github.com/aas-core-works/aas-core3.0rc02-react-editor

### AASX Package Explorer
Official tool for opening / editing AASX files.
Pre-build binaries available for Windows 10.

https://github.com/admin-shell-io/aasx-package-explorer

### AASX Server
Official AAS server which offers some proprietary endpoints.
Pre-build binaries available.

https://github.com/admin-shell-io/aasx-server

### BaSyx Java V2 Server
Offers off-the-shelf components to directly deploy:
* Repository,
* Submodel Repository,
* ConceptDescription Repository,
* Environment, and
* Registry.

Images available at Dockerhub.

https://github.com/eclipse-basyx/basyx-java-server-sdk

### NOVAAS

Web-based GUI to inspect an AAS.
Image available at Dockerhub.

https://gitlab.com/novaas/catalog/nova-school-of-science-and-technology/novaas

## Documentation 📝

### Specifications

https://industrialdigitaltwin.org/content-hub/downloads

### Tutorials

tbd.

## Testing

We list here data sets and testing tools which you can use for testing & development.

### AAS Core Testgen

Generates test data procedurally by property-based and combinatorial data generation.

Supports JSON and XML.

Provides test data for different versions of the AAS meta-model:
* v3.0: https://github.com/aas-core-works/aas-core3.0-testgen
* v3.0RC02: https://github.com/aas-core-works/aas-core3.0rc02-testgen

### Test Engines

Official test engines for the AAS. Provides functions to
* Check that your JSON, XML or AASX file is compliant to the standard
* Check that your REST API implementation is compliant to the standard

Implements v3.0.

* https://github.com/admin-shell-io/aas-test-engines
