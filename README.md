# IaC Bootstrap

Multi-Cloud Infrastructure as Code bootstrap repository

## Motivation

Every time when you start a new journey with IaC you have to answer a lot of
questions like how to organize your code files? how to manage state-files?
do I have to run terraform locally or do I need a CI server for that?
Most of the popular IaC tools will not provide you a standardized way
of organizing your code.
This repository serves as a starting point for your Infrastructure as Code
based on [Terraform](https://terraform.io). No matter what cloud provider you
are using, you will keep all of your code files in one place.
In fact this is not a real cloud-agnostic solution, because the code for
different cloud providers is various due to different resources
and their specifics. Anyway you still be able to use the same syntax,
constructions, and code style for it.

## Features

* Easiest way to start your project from scratch
* A tons of documentation inside
* Minimum requirements - you only need docker installed


## TOC

* [live](src/live/README.md)
    * [live/aws-acme](src/live/aws-acme/README.md)
    * [live/aws-acme/global](src/live/aws-acme/global/README.md)
    * [live/aws-acme/us-east-1](src/live/aws-acme/us-east-1/README.md)
    * [live/gcp-foobar/global](src/live/gcp-foobar/global/README.md)
    * [live/gcp-foobar/us-west1](src/live/gcp-foobar/us-west1/README.md)
* [modules](src/modules/README.md)
    * [modules/foo](src/modules/foo/README.md)