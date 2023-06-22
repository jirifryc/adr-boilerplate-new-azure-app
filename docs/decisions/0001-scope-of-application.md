# Scope of application

* Status: proposed
* Date: 2023-06-17

## Context and Problem Statement

The most critical step in deciding about running application in Cloud is defining their scope in relation to regions. This will infulence availability, speed, recovery scenarios, etc.

## Decision Drivers

* Do we need fallback solution? If yes that what kind of solution?
* Do we need to store data in specific country?
* Do we need to support different login in relation to region?

## Considered Options

* Single region without redundancy
* Single region with zone redundancy
* Single region with fallback region for backup
* Single region with fallback region for readonly access
* Single region with fallback region that can replace primary region
* Multiple regions setup

## Decision Outcome

Chosen option: "", because comes out best.

## Links

* https://jirifryc.cz/Cloud/Handbook/Cloud_scope_of_application/
