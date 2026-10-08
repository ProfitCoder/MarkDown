---
title: Readme.md

---

# Nebula DB Documentation Project

This is for a DataBase for a high tech performance, developed to act quick and with tolerance on the erros.

![built](https://img.shields.io/badge/build-passing-brightgreen)
![version](https://img.shields.io/badge/version-2.4.1-blue)
![license](https://img.shields.io/badge/license-Apache--2.0-orange)

## Indice

- [Arquitecture](#Architecture)
- [Components]()
- [Instalation]()
- [Configuration]()
- [Api]()
- [Diagram]()
- [Task]()
- [license]()

## Architecture

This DataBase uses a distributed form, that is done by the next services:

* API Gateway
    * Point for external request.
    * Manage the traffic
* Auth Service
    * It manages the authentification and the authorization
    * It sends and validate access tokens
* Query engine
    * Analyze and executes queries
    * It moves different operations between storage nodes
* Storage nodes
    * Storage data information on paper
    * Allows reaplication and horizontal scalability
* Monitoring
    * Get system metrics.
    * Generate alerts between erros and service degragation


| Components | Languaje | State | Version | Dependence |
|------------|----------|-------|---------|------------|
