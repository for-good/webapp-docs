# Q1 API

For this stage of the project we have pretty minimal requirements for the API; however, we DO need to setup the foundation of the API layer, for us to have initial code and API service available to communicate between the isgood.ai webapp, and the isgood.ai platform \(DS data brain\).

## Base API Service

Default communication for webapp and platform is JSON, so looking at options we can start looking at the following around easy to manage, deploy and contribute Open-API frameworks:

* [https://jsonapi.org/](https://jsonapi.org/)
* [https://swagger.io/specification/](https://swagger.io/specification/)
* [https://cube.dev/](https://cube.dev/)

## Functionality for Q1 Release

1. WebApp sends first four fields of project profile info to the API.
2. Platform receives the JSON text and processes it.
3. Returns list of platform indicatorIDs to WebApp and is stored as recommended indicatorIDs against the project.

