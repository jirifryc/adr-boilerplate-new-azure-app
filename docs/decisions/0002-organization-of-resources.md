# Organization of application resources

* Status: proposed
* Date: 2023-06-17

## Context and Problem Statement

Second architecture decision that we should do on route to deployment in cloud is decision about structure of our cloud. We can be often limited by what we can do and often we are unable to change higher layers of organization, like management groups, but we still need to record how we will organize our resources and why we could not or didn´t want to use different approach.

## Decision Drivers

* Some cloud resources cannot be moved later
* Easier navigation and understanding of your resources

## Considered Options

* Seperating environments on resource group level
* Seperating environments on subscription level, using resource group seperation for seperating applications.
* Seperating environments on management group level, leaving subscriptions and resource groups for seperating applications

## Decision Outcome

Chosen option: "", because comes out best.

## Links

* https://jirifryc.cz/Cloud/Handbook/Organization_of_resources/
