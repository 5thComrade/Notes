
# JavaScript Design Patterns - Book

These are my personal notes from a book I read about JavaScript Design Patterns.

## Chapter 1. Introduction to Design Patterns

"Good code is like a love letter to the next developer who will maintain it!"

A pattern is a reusable solution template that you can apply to recurring problems and themes in software design.

Learning and using design patterns is mainly advantageous for developers because of the following:

- Patterns are proven solutions.
    
    They are the result of the combined experience and insights of developers who helped define them. They are time-tested approaches known to work when solving specific issues in software development.

- Patterns can be easily reused.

    A pattern usually delivers an out-of-the-box solution you can adopt and adapt to suit your needs. This feature makes them quite robust.

- Patterns can be expressive.

    Patterns can help express elegant solutions to extensive problems using a set structure and a shared vocabulary.

- Patterns assist in preventing minor issues that can cause significant problems in the application development process.

- Patterns provide generalized solutions, documented in a fashion that doesn’t require them to be tied to a specific problem.

- Some patterns can decrease the overall code file-size footprint by avoiding repetition.

- Patterns add to a developer’s vocabulary, which makes communication faster.

- Popular design patterns can be improvised further by harnessing the collective experiences of developers using those patterns and contributing back to the community.

---

## Chapter 2. “Pattern”-ity Testing, Proto-Patterns, and the Rule of Three

### What is a Proto-Pattern?
A pattern that has not yet conclusively passed the “pattern”-ity tests is usually referred to as a proto-pattern.

Alternatively, the individual(s) sharing the pattern may not have the time or interest in going through the “pattern”-ity process and might release a short description of their proto-pattern instead. Brief descriptions or snippets of this type of pattern are known as patlets.

A pattern may be considered “good” if it does the following:

- Solves a particular problem

    Patterns are not supposed to just capture principles or strategies. They need to capture solutions. This is one of the most essential ingredients of a good pattern.

- Does not have an obvious solution

    We can find that problem-solving techniques often attempt to derive from well-known first principles. The best design patterns usually provide solutions to issues indirectly—this is considered a necessary approach for the most challenging problems related to design.

- Describes a proven concept

    Design patterns require proof that they function as described, and without this proof, the design cannot be seriously considered. If a pattern is highly speculative in nature, only the brave will attempt to use it.

- Describes a relationship

    In some cases, it may appear that a pattern describes a type of module. Despite what the implementation looks like, the official description of the pattern must describe much deeper system structures and mechanisms that explain its relationship to code.

### Rule of Three

One of the additional requirements for a pattern to be valid is that it displays some recurring phenomenon. You can often qualify this in at least three key areas, referred to as the rule of three.

- Fitness of purpose

    How is the pattern considered successful?

- Usefulness

    Why is the pattern considered successful?

- Applicability

    Is the design worthy of being a pattern because it has broader applicability?

---
