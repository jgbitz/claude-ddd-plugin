# Domain-Driven Design (DDD) Plugin

Provides systematic analysis tools for DDD strategic design, helping produce
domain analysis documents through structured questioning and interviews.

## Skills

### `ddd-strategic-design`

A DDD strategic design guide that assists with domain analysis through four
phases:

**Workflow:**

1. **Input Diagnosis** - Analyze existing information, identify gaps, and ask clarifying questions
2. **Domain Exploration** - Discover business concepts, boundaries, and rules through progressive questioning
3. **Interview Planning** - Generate interview question sets for PMs, domain experts, and end users
4. **Output Production** - Produce Bounded Context analysis, Context Map, and Ubiquitous Language

**Use Cases:**

- Analyzing system domain boundaries
- Planning stakeholder interviews
- Extracting domain knowledge from chaotic information
- Building standard DDD strategic documents

**References:**

Includes interview question templates and output format guides:

- `pm-questions.md` - Product Manager interview framework
- `expert-questions.md` - Domain expert interview framework
- `user-questions.md` - End user interview framework
- `output-templates.md` - Document output templates

## Questioning Principles

- Go from broad to narrow, one question at a time
- Use "why" to uncover business rules
- Use "what if" to discover edge cases
- Use "who" to identify stakeholders

## Notes

- Best suited for complex domains; simple systems may not need this
- Requires close collaboration with business experts
- Domain boundaries will adjust as understanding deepens

## Version History

See [CHANGELOG.md](./CHANGELOG.md) for detailed version change records.
