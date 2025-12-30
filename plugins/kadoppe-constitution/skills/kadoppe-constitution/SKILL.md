---
name: kadoppe-constitution
description: "ALWAYS apply this skill for ANY software development task. Triggers: implement, create, build, add, write, code, function, class, component, API, feature, fix, bug, debug, refactor, improve, clean, review, check, design, architect, structure, test, endpoint, module, service, handler, controller, model, schema, migration, deploy, configure. This skill enforces kadoppe's development principles for all coding work."
---

# Software Development Constitution

This constitution defines the fundamental principles that govern all software development work. These principles are non-negotiable and must be followed at all times.

## Article 1: Simplicity First

1. **YAGNI (You Aren't Gonna Need It)**: Do not implement features until they are actually needed.
2. **Minimal Solution**: Always choose the simplest solution that solves the current problem.
3. **No Premature Abstraction**: Avoid creating abstractions for hypothetical future requirements. Three similar lines of code is better than a premature abstraction.
4. **Delete Over Comment**: Remove unused code instead of commenting it out.

## Article 2: Code Quality

1. **Readability Over Cleverness**: Code should be easy to read and understand. Avoid clever tricks.
2. **Self-Documenting Code**: Code should explain itself through clear naming and structure. Comments are for "why", not "what".
3. **Single Responsibility**: Each function, class, and module should have one clear purpose.
4. **Consistent Style**: Follow the project's established conventions. Don't mix styles.

## Article 3: Reliability

1. **Fail Fast**: Detect errors as early as possible and fail with clear error messages.
2. **Defensive at Boundaries**: Validate input at system boundaries (user input, external APIs). Trust internal code.
3. **Test Critical Paths**: Ensure critical functionality is tested. Tests should be maintainable.
4. **No Silent Failures**: Never swallow errors silently. Log or handle them explicitly.

## Article 4: Security

1. **Security by Default**: Choose secure defaults. Security should not be opt-in.
2. **Never Trust User Input**: Always sanitize and validate external input.
3. **Least Privilege**: Grant minimum necessary permissions.
4. **No Secrets in Code**: Never hardcode credentials, API keys, or sensitive data.

## Article 5: Maintainability

1. **Boy Scout Rule**: Leave code better than you found it, but only if it's directly related to your task.
2. **Explicit Over Implicit**: Make dependencies and side effects explicit.
3. **Avoid Deep Nesting**: Keep code flat. Extract complex conditions into well-named functions.
4. **Small Changes**: Make incremental, focused changes. Large rewrites are risky.

## Article 6: Pragmatism

1. **Working Software First**: Delivering working software takes priority over perfect architecture.
2. **Context Matters**: Apply principles with judgment. Rules have exceptions in specific contexts.
3. **Technical Debt is Real**: Acknowledge shortcuts. Document them and plan to address them.
4. **Measure Before Optimize**: Don't optimize without evidence of actual performance problems.

---

