# Application runtime

* Status: proposed
* Date: 2023-06-17

## Considered Options

* Virtual machine
* Azure Functions
* Azure Application Services
* Azure Container Instances
* Azure Container Applications
* Azure Kubernetes Services
* Own Kubernetes on VMSS

## Decision Outcome

Chosen option: "", because comes out best.

## Pros and Cons of the Options

### Virtual machine

* Good, because supports lift and shift
* Bad, because hard to maintain

### Azure Functions

* Good, because it is ideal solution for event driven workload
* Good, because it is ideal solution for short lived workload
* Bad, because long lived workload cost significantly more then in other resources
