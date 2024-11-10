# Architecture

Training from ardalis: "Getting Started: Modular Monoliths in .NET"

## Monolith

### Monolith pro's

- simple to create
- simple to deploy

### Monolith cons's

- hard to keep the code clean
- layered archicture helps

## Micro service

### Microservice pro's

- scale

### Microservice cons's

- complex
- expensive

## Modular Monolith

### Modular Monolith pro's

- advantages of monolith - better maintainable
- well defined, loosely coupled modules
- if needed, parts can be converted to separate modules (like microserivce, see MassTransit)

### Modular Monolith cons's

- easier to keep the code clean

## Event Streaming is not Event Sourcing

Event Streaming is not Event Sourcing!
<https://event-driven.io/en/event_streaming_is_not_event_sourcing/>

## Vertical Slices

<https://github.com/boeschenstein/VerticalSlices>

## CQS, CQRS

> CQRS takes the defining principle of CQS and extends it to specific objects within a system, one retrieving data and one modifying data. CQRS is the broader architectural pattern, and CQS is the general principle of behaviour.

CQRS Levels: <https://enterprisecraftsmanship.com/posts/types-of-cqrs/>
- Type 0: no CQRS
- Type 1: separated class structure
- Type 2: separated model
- Type 3: separated storage

# Draw, Charts

- UML <https://holub.com/uml/>
- 4+1 architectural view model <https://en.wikipedia.org/wiki/4%2B1_architectural_view_model>
  - Logical view
  - Process view
  - Development view
  - Physical view
  - Scenarios
 
# Verify architecture

- <https://www.plainionist.net/Dependency-Governance-DotNet/>
- <https://stackoverflow.com/questions/17226311/is-there-a-way-to-prevent-certain-references-from-being-included-on-a-project>
- <https://www.ben-morris.com/writing-archunit-style-tests-for-net-and-c-for-self-testing-architectures/>
- ArchUnit <https://archunitnet.readthedocs.io/en/stable/>
- NsDepCop <https://github.com/realvizu/NsDepCop/>
- NetArchTest <https://github.com/BenMorris/NetArchTest>
