# Why LLD?
    LLD is not just about writing code that works, it’s about writing code that’s modular, testable, extensible, 
    and easy to reason about as the system grows.

# HLD vs LLD
    HLD foucses on System, Architecture, Infra and Components - What?
    LLD focuses on Implementation - how ?

# lld 'abilities
    maintainability: clean, debug, test, collaboration, extension (low coupling, high cohesion)
    reusability
    scalability

# lld trade-off's
    - Deep inheritance vs Composition
    - Encapsulation / Rich Domain model vs Anemic model + Service Layer
    - Interface abstraction vs Direct concrete class
    - Normalized vs Denormalized data structures
    - Thread Safety vs Performance/Simple Design
    - Precomputation/caching vs On demand calculation

# OOP fundamentals
    classes & objects
    enums
    interfaces
    encapsulation
    abstraction
    inheritance
    polymorphism

# class relationships
    association
    aggregation
    composition
    dependency
    realization

# design principles
    DRY
    KISS
    SOLID: Single Responsibility, Open/Closed, Liskov's, Interface Segregation, Dependency Injection 
    YAGNI
    Law of Demeter - talk to your friends only, Avoid chaining objects & properties in a single statement
    Single Responsibility - A class should have one, and only one, reason to change. 
    GRASP - "General Responsibility Assignment Software Patterns"
        - creator, information expert, low coupling, high cohesion, controller, pure fabrication, indirection, polymorphism
    Composition Principle: Composition over inheritance
    Separation Of Concerns
    Coupling vs Cohesion
    what are they for? when can you violate?

# UML
    Class Diagram 
    Use Case Diagram
    Sequence Diagram
    Activity Diagram

# design patterns
    ## creational
        - Singelton
        - Factory Method
        - Builder
        - Abstract Factory
        - Prototype    
    ## structural
        - Adapter
        - Facade
        - Decorator
        - Composite
        - Proxy
        - Bridge
        - Flyweight
    ## behavioral
        - Iterator
        - Observer
        - Strategy
        - Command
        - State
        - Template Method
        - Visitor
        - Mediator
        - Momento
        - Chain Of Responsibility

# lld interview template
    Clarify (Functional Requirements/Use Cases)
    Identify Entities (Core Objects & Relationships)
    Define Responsibilities/Behavior
    Implement
        - Class Design
        - API's/Interface/Interaction
        - Add Extensions
        - Design Patterns
        - Concurrency/Edge Cases
    Summarize Trade-off's
        - performance vs readability
        - flexibility vs simplicity
        - When interviewer asks - Why you choose X? 
            - state alternatives - we could do Y instead of X.
            - prod - picked X because it optimizes A & B which match current requirements
            - cons - X comes at cost C & D
            - switch/mitigate - if system later needs E I will revisit Y or mitigate C/D using Z
    What are they checking for? 
        - structure, build (maintainable, extensible) code
        - following design principles/patterns
        - can other developers trust?
        - Use 2–3 such trade-offs per problem; depth matters more than listing many.

# Mental "LLD checklist"
    Requirements > Use cases > Core entities > Relationships
    Class diagram > APIs > Interactions
    Extensibility > Design patterns > Trade-offs
    Error handling > Concurrency > Caching > Rate limits (if needed)

# LLD Problems:
    ## Easy:
    Stack Overflow: https://blog.algomaster.io/p/how-to-answer-a-lld-interview-problem
    
    


# References:
    trade-off's: https://www.perplexity.ai/search/give-me-few-concrete-examples-oDvRQ.zIRpy08iXx3lQYaQ
    hld: https://algomaster.io/learn/lld/lld-vs-hld