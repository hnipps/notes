# Rigidity, a code smell

This note describes rigidity as it relates to software development. It's one of the key, high-level code smells (AKA symptom of poor software design) identified in Agile Software Development[^1].

You can identify a rigid design *via* the following yardsticks:
- Small changes to a codebase take a lot of effort, often much more than was estimated for that task
- A change in one module requires changes to be made in dependent modules
  - The more modules that must be changed, the more rigid the design

### Key Quotes

- > "It was more complicated than I thought!" [^2]


### References

- [^1]: Agile Software Development, Robert C. Martin
- [^2]: Every developer ever

### Related Notes
- [Agile Design](./agile-design.md)