# Requirements Analysis

> _Understanding individual requirements is not enough. Engineers must determine whether those requirements collectively describe a system that can be confidently designed._

---

# Why Requirements Analysis Exists

Understanding requirements does not guarantee that a system is ready for design.

Individual requirements may appear correct while the overall system remains inconsistent, incomplete, or difficult to reason about.

Requirements Analysis exists to validate the engineering understanding of the problem before Solution Design begins.

Its purpose is not to create a solution.

Its purpose is to determine whether the current understanding of the problem is coherent enough to design.

---

# The Engineering Goal

Requirements Discovery asks:

> _What does the business need?_

Requirements Analysis asks:

> _Do these requirements collectively describe a coherent system?_

The focus shifts from validating individual requirements to understanding the behavior that emerges when all requirements interact.

---

# Analyzing the System, Not the Requirements

Experienced engineers rarely analyze requirements in isolation.

Instead, they construct an engineering model of the system and continuously challenge it.

The objective is to understand:

- System behavior
- Responsibility boundaries
- Interactions between responsibilities
- Missing behaviors
- Conflicting behaviors
- Unnecessary complexity

The analysis is performed on the system described by the requirements, not on the requirements themselves.

---

# Understanding Behavior

Requirements gain meaning only when viewed as part of the complete system behavior.

Engineers often reconstruct the expected behavior of the system before making design decisions.

This process helps reveal:

- unsupported transitions
- missing requirements
- misplaced requirements
- conflicting responsibilities
- unnecessary requirements

The technique used to understand behavior is not important.

Whether through discussion, journeys, scenarios, event modeling, diagrams, or mental simulation, the objective remains the same:

Understand how the system behaves before deciding how it should be built.

---

# Discovering Responsibility Boundaries

One of the primary outcomes of Requirements Analysis is discovering natural responsibility boundaries.

Boundaries are not invented during analysis.

They emerge from understanding how the system behaves.

Each responsibility should remain internally coherent while interacting predictably with other responsibilities.

Understanding these relationships significantly reduces uncertainty before Solution Design.

---

# Challenging the Engineering Model

Requirements Analysis is an iterative process.

Engineers continuously challenge their own understanding by asking questions such as:

- Does every behavior have sufficient support?
- Does every responsibility have a clear owner?
- Are interactions consistent?
- Does every requirement contribute meaningful behavior?
- Can new scenarios be incorporated without fundamentally changing the model?

The objective is not to eliminate every question.

The objective is to expose weak assumptions before design begins.

---

# Internal and External Validation

A coherent model is not automatically a correct model.

First, the engineering model must become internally consistent.

Then it should be challenged by experienced engineers, domain experts, and stakeholders.

Constructive criticism helps expose assumptions, overlooked scenarios, and weak reasoning.

A successful review does not prove the model is correct.

It increases confidence that the model accurately represents the problem.

---

# When Analysis Is Complete

Requirements Analysis is complete when the engineering model becomes difficult to break.

Minor improvements should always remain possible.

However, meaningful technical or business criticism should no longer require fundamental changes to:

- system behavior
- responsibility boundaries
- interactions
- overall engineering understanding

At this point, the remaining questions primarily belong to Solution Design rather than Problem Analysis.

---

# Engineering Conclusion

Requirements Analysis is the process of building and validating a defensible engineering model of the system.

The objective is not to prove that the analysis is correct.

The objective is to produce a model that remains coherent, understandable, and defensible under meaningful technical and business criticism, providing sufficient confidence to begin Solution Design.
