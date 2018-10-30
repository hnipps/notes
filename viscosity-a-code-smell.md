# Viscosity, a code smell
This note aims to outline viscosity as it relates to software development, specifically [agile design](./agile-design).

Viscosity is a code smell (AKA symptom of poor software design) that comes in 2 forms:
- Viscosity of the software
- Viscosity of the environment

Viscous software is characterised by:
- It being harder to write code that preserves the design than write code that doesn't
  - It's easier to write "hacky" fixes than actually write good code

A viscous environment is characterised by:
- Long compile times
- Cumbersome software version control systems
  - Both of these tempt software developers to make changes that avoid recompiling and minimise code check-ins, regardless of whether the software design is preserved

### Key Quotes
- "A viscous project is a project in which the design of the software is hard to preserve."[^1]

### References
- pp. 88, Agile Software Development, Robert C. Martin
- [^1]: pp. 89, Agile Software Development, Robert C. Martin

### Related Notes
- [Agile Design](./agile-design.md)
