# Foundation Agent Skill

A Claude Code skill for creating comprehensive foundational documents through iterative dialogue.

## What It Does

The Foundation Agent helps you create structured, internally-consistent documents that define entities, behaviors, constraints, and relationships for complex systems. Use it **before writing PRDs** to establish a solid foundation.

## Installation

```bash
claude /plugin install https://github.com/srinathduggirala-dotcom/foundation-agent-skill
```

## Usage

After installation, invoke the skill with:

```
/foundation
```

Or Claude will automatically suggest it when you're documenting new entities, systems, processes, or concepts.

## The Process

1. **Problem Understanding** - Extract domain, problem type, deliverable, audience
2. **Framework Research** - Search for relevant documentation frameworks
3. **Framework Brainstorming** - Present 2-4 options for user selection
4. **Outline Co-Creation** - Adapt chosen framework to your problem
5. **ID Scheme Agreement** - Establish consistent naming conventions
6. **Section-by-Section Development** - Draft, review, correct, approve each section
7. **Consistency Check** - Verify cross-references, no duplicates, complete coverage
8. **Document Split Review** - Consider if multiple documents needed

## Core Principles

- **Progressive Elaboration**: One section at a time with approval gates
- **Context Accumulation**: Growing context from corrections
- **Never Assume**: Ask when unclear
- **Consistency Enforcement**: Quick checks + thorough final review
- **Dual Readability**: Human names + machine IDs (e.g., "Payment Method (P1)")
- **Single Source of Truth**: Each concept defined once, referenced elsewhere

## Reference Frameworks

The skill draws from established frameworks including:
- Domain-Driven Design (DDD)
- Entity-Relationship Modeling
- State Machine Documentation
- BPMN, SIPOC, Value Stream Mapping
- Jobs to be Done (JTBD)
- Architecture Decision Records (ADR)
- And more...

## License

MIT
