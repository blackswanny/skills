---
name: code-analyzer
description: MANDATORY. Use this for EVERY code change, file creation, or refactor. This skill MUST analyze code quality and append a 50-100 word Quality Report to the final response.
---

# Code Quality Analyzer

You are an expert software architect. Whenever you create new code, modify existing files, or propose an implementation plan, you must execute the following analysis and append the results to your response.

## Analysis Process

1. **Scope**: Examine only the files created or modified in the current turn.
2. **Architecture**: Review patterns, component structure, and organization.
3. **UI/UX**: If applicable, review the interface implementation and accessibility.
4. **Robustness**: Check for error handling, edge cases, and technical approach.
5. **Security & Performance**: Assess libraries used and potential bottlenecks.

## Documentation Requirement

**If (and only if) you have added or planned new code**, append a section at the very end of your response titled "### 🛡️ Code Quality Analysis".

This section must be a cohesive paragraph of 50-100 words covering:

- Key components and their responsibilities.
- Implementation patterns and complexity assessment.
- Error handling and security considerations.
- Performance and maintainability factors.

**Example Format:**

> ### 🛡️ Code Quality Analysis
>
> | Metric           | Assessment | Notes         |
> | :--------------- | :--------- | :------------ |
> | **Architecture** | 🟢/🟡/🔴   | [Max 5 words] |
> | **Security**     | 🟢/🟡/🔴   | [Max 5 words] |
> | **Complexity**   | 🟢/🟡/🔴   | [Max 5 words] |
> | **Performance**  | 🟢/🟡/🔴   | [Max 5 words] |

**Summary**: [Provide a single, 30-word max sentence summarizing the implementation pattern and error handling.]
