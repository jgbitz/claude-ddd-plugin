# Domain Expert Interview Questions

The goal of the domain expert interview is to uncover deep business rules,
terminology definitions, and complex domain logic. This knowledge is critical
for building the Ubiquitous Language and identifying Bounded Context boundaries.

## Phase 1: Terminology and Concept Clarification

**Purpose: Establish precise domain vocabulary and discover cases of homonyms or
synonyms**

1. What are the most commonly used professional terms in your work?
2. [For a specific term] What exactly does this word mean in your domain?
3. Are there cases where the same word means different things in different contexts?
4. Are there terms that non-experts commonly misunderstand?
5. Which terms are industry standard, and which are specific to this company?

**Follow-up techniques:**

- "Can you give a specific example?" - Validate understanding with examples
- "How is this term different from [another similar term]?" - Distinguish subtle differences
- "What do newcomers commonly misunderstand this term to mean?" - Identify common misconceptions

## Phase 2: Business Rules and Invariants

**Purpose: Uncover core business rules, invariants, and domain constraints**

1. In your domain, what rules must "absolutely never be violated"?
2. Under what circumstances is [a certain operation] not allowed?
3. If [a certain rule] is broken, what problems occur?
4. What is the source of these rules? (Regulations, business conventions, technical limitations?)
5. Can these rules change? Under what circumstances?

**Follow-up techniques:**

- "Why does this rule exist?" - Understand the reasoning behind the rule
- "Does this rule have exceptions?" - Discover special cases
- "Who is affected if this rule is not followed?" - Understand the impact scope

## Phase 3: Domain Events and State Transitions

**Purpose: Identify key domain events and understand entity lifecycles and state
machines**

1. In your daily work, what are the important "something happened" moments?
2. When [a certain event] occurs, what typically happens next?
3. What states does [a certain entity] go through? How does it transition from one state to another?
4. Under what circumstances does a state transition fail?
5. Which events require immediate notification to other people or systems?

**Follow-up techniques:**

- "Can this event be reversed?" - Understand reversibility
- "Does the order of events matter?" - Identify ordering constraints
- "What happens if this event is not recorded?" - Understand the event's importance

## Phase 4: Calculations and Decision Logic

**Purpose: Understand complex formulas, scoring mechanisms, or decision
processes**

1. How is [a certain value] calculated?
2. When making [a certain decision], what factors do you consider?
3. Are there rules of thumb or heuristics?
4. Does this calculation/decision have a precise formula, or does it rely on expert judgment?
5. Under what circumstances do calculation results need manual review?

**Follow-up techniques:**

- "Can you walk through a specific example of the calculation?" - Validate understanding
- "Which parameters in this formula are most critical?" - Identify core factors
- "Are there boundary values or special cases that need special handling?" - Discover edge conditions

## Phase 5: Exceptions and Edge Cases

**Purpose: Discover easily overlooked special situations — these often reveal
hidden complexity**

1. In actual work, what "exceptional situations" require special handling?
2. What are the most troublesome edge cases?
3. Where do newcomers most commonly make mistakes?
4. Are there situations that "theoretically shouldn't happen but actually do"?
5. When the system encounters an error, how do you diagnose and handle it?

**Follow-up techniques:**

- "How often does this situation occur?" - Assess frequency
- "What is the standard procedure for handling this?" - Understand handling mechanisms
- "What are the risks if this is handled poorly?" - Assess severity

## Phase 6: Data and Information Flow

**Purpose: Understand how data flows, which data is the authoritative source,
and which is derived**

1. Where is the authoritative source (Source of Truth) for this data?
2. Where is this data synchronized to?
3. What are the timeliness requirements for this data? (Real-time, near real-time, eventually consistent?)
4. If data in two places is inconsistent, which takes precedence?
5. How is data completeness and accuracy verified?

**Follow-up techniques:**

- "Can this data be modified? Under what circumstances?" - Understand mutability
- "How long does this data need to be retained?" - Understand lifecycle
- "Who has permission to access/modify this data?" - Understand permission boundaries

## Phase 7: Interactions with Other Domains

**Purpose: Identify boundaries and integration points between Bounded Contexts**

1. Which other departments/teams does your work require collaboration with?
2. What information do you need from other systems?
3. Who uses the information you produce?
4. In collaboration, have you encountered situations where "they use different terms than we do"?
5. What are the most common problems when collaborating across departments?

**Follow-up techniques:**

- "How do you hand off information between teams?" - Understand integration methods
- "Does the information format provided by others meet your needs?" - Discover adaptation issues
- "If their system has problems, how does that affect your work?" - Understand coupling

## Phase 8: Time and Concurrency Considerations

**Purpose: Understand time-related business rules and handling logic under
concurrent conditions**

1. Does this operation have time constraints? (Deadlines, expiration dates, time sensitivity?)
2. What happens if two people perform [a certain operation] simultaneously?
3. How is historical data handled? Does it need retroactive modifications?
4. Are there concepts of "effective dates" or "scheduled execution"?
5. Do time zones or business hours affect business logic?

**Follow-up techniques:**

- "What happens if the operation exceeds the time limit?" - Understand timeout handling
- "Can you go back to a certain point in time to view the state?" - Understand historical tracking needs
- "Can this operation be scheduled for later execution?" - Understand timing flexibility

## Post-Interview Summary

From the domain expert interview, you should be able to compile:

1. **Ubiquitous Language Glossary** - Precisely defined domain terms
2. **Core Business Rules List** - Invariants and constraints
3. **Domain Events Catalog** - Key business events and their trigger conditions
4. **State Machine Diagrams** - State transitions for important entities
5. **Exception Handling Mechanisms** - Edge cases and exceptional situations
6. **Context Boundary Signals** - Terminology conflicts, team boundaries, differences in data authority sources

Remember: Domain experts provide deep knowledge but may lack a global
perspective. This needs to be combined with PM and user interviews to build a
complete understanding of the domain.
