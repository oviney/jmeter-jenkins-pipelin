# Running Test Containers
In this micro tutorial, we'll show you how to run a:

1. JMeter Test Plan in Docker Test Container

# Let's talk about the receipe

## Performance Testing
For JMeter, we'll be using Blazemeter Taurus default Docker container, defining a custom Dockerfile for our Test Container.  For reporting, we'll use Blazemeter's free cloud hosted tool.

## CI / CD
For this tutorial, we'll demonstrate how to build, ship and run our containers using Azure DevOps.  The basic setup will be use Azure DevOps, build a pipeline stored in Github, use Azure Container Instances to run the Docker Container, then tear down.

# Let's talk about the integration with DevOps
Each Test Container will be derived from a Product Team, so for the sake of this micro tutorial, we'll assume the same is true.

Performance Test Case: Basic Web Performance Test plan, hitting some basic endpoints using JMeter

Functional Test Case:  Navigate to test website, perform some basic assertions

## Sum it all up
You can either manually trigger the pipeline or you can make a chance to the source code (test artefacts).

## Here is a quick vido
You can watch this quick video that summarizes the full micro tutorial.
