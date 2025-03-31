![image](https://github.com/user-attachments/assets/6842865a-f15a-4308-8f65-c6ff8e451b88)# Architecture

Training from ardalis: "Getting Started: Modular Monoliths in .NET"

## Monolith

### Monolith pro's

- simple to create
- simple to deploy

### Monolith cons's

- hard to keep the code clean
- layered architecture helps

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

- "all models war wrong, but some are useful"
  - <https://en.wikipedia.org/wiki/All_models_are_wrong>
- Editor <https://draw.io/>
- UML <https://holub.com/uml/>
- Start with Wardley Mapping <https://learnwardleymapping.com/>
- 4+1 architectural view model
  - Wiki <https://en.wikipedia.org/wiki/4%2B1_architectural_view_model>
  - Good introduction <https://www.youtube.com/watch?v=S9YbFdLdKxE>
  - Paper <https://www.cs.ubc.ca/~gregor/teaching/papers/4+1view-architecture.pdf>
  - 4+1 Views:
    - Logical view
    - Process view
    - Development view
    - Physical view
    - Scenarios/Use Cases

# Naming examples

Software Naming: The Ultimate Cheat Sheet: <https://medium.com/@santy/software-naming-the-ultimate-cheat-sheet-b6bccc1d5373>

Some Service Suffixes:
Manager, Handler, Provider, Builder, Factory, Cache, Adapter, Wrapper, Monitor, Controller, Dispatcher, Utility, Resolver, Facade, Proxy, Strategy, Validator, Processor, Listener, Observer, Decorator, Service, Formatter, Comparator, Reader, Writer, Scanner, Generator, Parser, Interpreter, Visitor, Calculator, Connection, Session, Transaction, Resource, Template, Context, Emitter, Collector, Renderer, Transformer, Encoder, Decoder, Subscriber, Publisher, Engine, Loader, Executor, Verifier, Compiler, Serializer, Deserializer, Connector, Mediator, Filter, Command, Query

# Verify architecture

- <https://www.plainionist.net/Dependency-Governance-DotNet/>
- <https://stackoverflow.com/questions/17226311/is-there-a-way-to-prevent-certain-references-from-being-included-on-a-project>
- <https://www.ben-morris.com/writing-archunit-style-tests-for-net-and-c-for-self-testing-architectures/>
- ArchUnit <https://archunitnet.readthedocs.io/en/stable/>
- NsDepCop <https://github.com/realvizu/NsDepCop/>
- NetArchTest <https://github.com/BenMorris/NetArchTest>
