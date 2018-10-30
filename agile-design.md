# Agile Design for software development

Agile Design is a methodology that aims to developers build software in a way that allows for changing requirements, and for continuous improvement.

Agile Design is needed because requirements constantly change, they're the most volatitle part of software development. It's made up of a few key principles, now commonly known as the SOLID principles. They are as follows:

- Single Responsibility Principle (SRP)
- Open-Closed Principle (OCP)
- Liskov Subsitution Principle (LSP)
- Interface Segregation Principle (ISP)
- Dependency Inversion Principle (DIP)

The theory of Agile Design states that you should only apply these principles when symptoms of poor design (AKA code smells) are identified. The symptoms include:

- _[Rigidity](./rigidity.md)_ - The design is hard to change
- _[Fragility](./fragility.md)_ - The design is easy to break
- _[Immobility](./immobility.md)_ - The design is hard to re-use
- _[Viscosity](./viscosity-a-code-smell.md)_ - It's hard to do the right thing
- _Needless Complexity_ - Overdesign
- _Needless Repitition_ - Mouse abuse, copy-paste problems
- _Opacity_ - Disorganised expression, hard-to-understand code

Another key point of Agile Design is, _The Design_ isn't a specific diagram, or document, it's the source code itself. It might be supplemented by UML diagrams, architecture documentation, or any other kind of design doc, but these are not the design in and of themselves. The code is the design.

## Key Quotes

- > "Overconformance to the principles leads to the code smell of _Needless Complexity_."[^1]
- > "Agile design is a process, not an event."[^2]

[^1]: pp. 86, Agile Software Development, Robert C. Martin

[^2]: pp. 94, Agile Software Development, Robert C. Martin
