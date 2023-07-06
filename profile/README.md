## Automated Feedback System

This organization groups all the repositories linked to the implementation of an automated feedback system, which is part of MTU final year project of Romain Clemencon.

### TODO

Explain:
- Architecture
- How to host it locally
- How to run it locally
- How to mix cloud and local


## Versioning:

Any changes related to a full cloud environment will only be present in the V1.0 of any repositories. A repository might be ahead of another one, and therefore there will be a primary indicator to know which one is ahead.

### V1 - cloud architecture

The first version of this project will consist of the implementation conducted during the thesis for the final year project of my baschelor. As it is, V1.0 will consists of the version submitted with a few additional changes.
V1 repos might require to use cloud specific services. V1.0 will only rely to AWS services (e.g. DynamoDB, SQS, etc.).

### V2 - physical architecture (PRIMARY)

The "physical" architecture will only uses libraries, framework, tools and other utilities than can be installed locally on a machine. This will make it the easier version to use for free. For convenience, docker-compose will be used to setup and run the project in dev or production environment.

As of today, this version will be the main focus. In order to learn new technologies and avoid the constraint of cloud providers (especially the cost).

There will be an overlap before V2.0 where it will gradually implement new technologies locally whole still partially using some cloud services.