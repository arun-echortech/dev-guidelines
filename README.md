# Developer guidelines

- Build and maintain strong fundamentals in software engineering.
- Learn how to correctly and effectively leverage LLMs in your work.
- Take full responsibility for developer testing. It is the developer’s responsibility to ensure work is free of bugs.
- Begin development only after fully understanding all requirements and features. Clarify first if anything is unclear.
- Back up work regularly, commit frequently, backup pem files,`.env` files and secrets and any and all realated files, in a secure manner.
- Include a `claude.md` or `cursor/rules.md` file in every project and keep it updated at all times.
- Read every message in key channels such as scrum and general. These are mandatory communication channels.
- Do not use office laptops, licensed office software, or shared paid tools such as Claude for personal purposes.

---

## LLM use

### Core usage

- Clear task description
- Step-by-step prompting
- Constrain output format
- Iterative refinement

### Code work

- Generate tests first
- Small scoped changes
- Read existing code with summaries
- Explain diffs
- Rename and refactor by instruction

### Context handling

- Short prompts
- Relevant snippets only
- Break big tasks into chunks
- Compacting

### Error handling

- Ask model to find failure points
- Force it to reason before code
- Verify output with examples

### Safety

- No secrets in prompts
- Treat outputs as drafts
- Validate before running

---

## Frontend

- Using developer tools
- Debugging basics
- CSS fundamentals
- JavaScript promises, hoisting, objects
- HTTP status codes
- CORS
- Browser storage types: cookies, `localStorage`, `sessionStorage`, `IndexedDB`
- React fundamentals
- React re-rendering
- `useCallback`
- Memoization
- React context
- Complex state management
- Basic DNS records

---

## Backend and cloud

- SQL basics, PostgreSQL fundamentals, optimizing SQL queries, table design fundamentals, normal forms
- SQL vs NoSQL
- MongoDB basics
- Redis basics, when to use Redis
- Async processing concepts like Kafka, NestJS events, AWS SQS
- DevOps basics
- Networking fundamentals
- Backend debugging
- Test driven development
- Unit tests vs end-to-end tests
- GitHub Actions
- Deployments

