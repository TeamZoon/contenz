# conTenZ

## Concept

Contenz suppose be a CMS module of the TeamZoon software ecosystem.
It act as a micro-service to provide central control of all purpose contents use in any other modules, like website, blog, application, etc.

In order to achieve its functionality, there would be generally two main parts of contenz.
- A Content provider (API)
- A set of component/page generators for different use case

## Features

- One central place to control all purpose contents for all nodes of business
- Easy to build up any kind of page from scratch
- Blade fast revealing with pre-fetched server rendering page nodes
- Seamless interaction, page updates push on event
- Low cost deployment
- full scalability 

## Technical Stack

### Architecture

Universal device <-> Next.js + Apollo client <-> GraphCool

### Syntax

Typescript targeting ES2017

### Unit Testing

- Test runner framework: jest
- Assertion framework: jest
- Assertion style: expect
- Stub framework: jest
