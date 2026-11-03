# Python Developer Roadmap (2026)

A practical, project-based path from Python fundamentals to professional Python development.

This roadmap is a learning guide, not a certification checklist. Move through the stages in order, build the suggested projects, and revisit topics when a project exposes a gap.

## How to use this roadmap

- [ ] Pick one stage and work through its topics.
- [ ] Build the stage project without copying a complete solution.
- [ ] Add tests and document how to run the project.
- [ ] Track what you have completed by checking the boxes.
- [ ] Publish finished projects in separate repositories or clear folders.

**Suggested pace:** 4–8 hours per week. The timeline is intentionally flexible; consistency and working software matter more than speed.

## 1. Programming foundations

Learn the language and the tools used to work with it.

- [ ] Install a supported Python 3 version and use the official documentation.
- [ ] Variables, built-in types, operators, strings and input/output.
- [ ] Conditions, loops, comprehensions and pattern matching.
- [ ] Functions, arguments, return values, scope and recursion.
- [ ] Collections: lists, tuples, dictionaries and sets.
- [ ] Modules, packages, imports and virtual environments.
- [ ] Exceptions and basic debugging.
- [ ] Read and write text, CSV and JSON files.
- [ ] Git fundamentals: commits, branches, merges and pull requests.

**Practice projects**

- Command-line calculator
- Expense tracker that reads and writes CSV
- File organizer with safe dry-run mode

## 2. Intermediate Python

Build maintainable programs and understand how Python behaves.

- [ ] Object-oriented programming: classes, composition and inheritance.
- [ ] Iterators, generators, decorators and context managers.
- [ ] Type hints, generics and static type checking.
- [ ] Dataclasses, enums and useful standard-library modules.
- [ ] Logging and configuration through environment variables.
- [ ] Dependency management and reproducible environments.
- [ ] Code quality: formatting, linting and project structure.
- [ ] Unit testing with pytest, fixtures and parametrization.
- [ ] Mock external services and test failure paths.

**Practice project**

Build a small CLI application with a clean package structure, type hints, tests, logging and a documented setup process.

## 3. Professional development workflow

Learn to work on a codebase as part of a team.

- [ ] Use a \`src/\` layout where it makes sense.
- [ ] Write useful README files and API documentation.
- [ ] Use Git branches and small, focused pull requests.
- [ ] Add pre-commit checks for formatting and linting.
- [ ] Configure CI to run tests and quality checks.
- [ ] Manage secrets safely; never commit credentials.
- [ ] Understand semantic versioning and changelogs.
- [ ] Review code and respond constructively to review feedback.

**Practice project**

Package one of your earlier projects, add CI, publish installation instructions and create a tagged release.

## 4. APIs and backend development

Choose a framework and learn HTTP fundamentals before adding complexity.

- [ ] HTTP methods, status codes, headers and JSON.
- [ ] REST resource design, validation and pagination.
- [ ] Build an API with FastAPI or Flask.
- [ ] Request/response schemas and dependency injection.
- [ ] Authentication and authorization fundamentals.
- [ ] SQL fundamentals, schema design and indexes.
- [ ] Use SQLAlchemy or another well-supported data-access layer.
- [ ] Database migrations and transaction handling.
- [ ] Integration tests for routes and persistence.
- [ ] API documentation with OpenAPI.

**Practice project**

Build a task or inventory API with persistence, validation, authentication, migrations, tests and OpenAPI documentation.

## 5. Data, automation and integrations

Select the branch that best matches your interests.

### Data analysis

- [ ] NumPy and pandas fundamentals.
- [ ] Data cleaning, missing values and validation.
- [ ] Visualisation with Matplotlib or another plotting library.
- [ ] Reproducible notebooks and clear data provenance.

### Automation and web scraping

- [ ] HTTP clients, timeouts, retries and rate limits.
- [ ] HTML parsing and browser automation when necessary.
- [ ] Respect robots policies, terms of service and privacy.
- [ ] Store results in a database or structured files.
- [ ] Make jobs idempotent and observable.

### Data engineering

- [ ] Batch processing and file formats such as CSV, JSON and Parquet.
- [ ] SQL and data modelling.
- [ ] Pipeline orchestration concepts.
- [ ] Data quality checks and failure recovery.
- [ ] Distributed processing concepts; explore Spark when justified.

**Practice project**

Create a scheduled data pipeline that ingests a permitted public dataset, validates it, stores clean outputs and documents its failure/retry behaviour.

## 6. Deployment and operations

- [ ] Build and run an application with Docker.
- [ ] Configure environments and secrets outside source control.
- [ ] Deploy a small service to a cloud platform.
- [ ] Add health checks and structured logs.
- [ ] Understand basic monitoring, metrics and alerting.
- [ ] Add dependency and security checks to CI.
- [ ] Back up and migrate persistent data safely.

**Practice project**

Containerize and deploy your API, document its configuration, and add a CI workflow that runs tests before building the image.

## 7. Advanced topics (learn when needed)

- [ ] Async programming: \`async\`/\`await\`, event loops and concurrency trade-offs.
- [ ] Performance profiling before optimizing.
- [ ] Caching and background task processing.
- [ ] Architecture boundaries and dependency inversion.
- [ ] Security fundamentals: input validation, authorization and safe secret handling.
- [ ] Packaging and publishing reusable libraries.
- [ ] Design for observability and graceful failure.

Do not study every advanced topic up front. Choose based on the requirements of a real project.

## Portfolio checklist

A strong portfolio demonstrates complete, usable work rather than a large number of unfinished repositories.

- [ ] One well-tested Python package or CLI tool.
- [ ] One documented REST API with a database.
- [ ] One automation or data pipeline with validation.
- [ ] CI checks that run on every pull request.
- [ ] Clear READMEs with setup, usage, examples and limitations.
- [ ] Meaningful commits and focused pull requests.

## Recommended learning resources

Prefer primary documentation and use tutorials to supplement it.

- [Python official tutorial](https://docs.python.org/3/tutorial/)
- [Python standard library](https://docs.python.org/3/library/)
- [Python Packaging User Guide](https://packaging.python.org/)
- [pytest documentation](https://docs.pytest.org/)
- [FastAPI documentation](https://fastapi.tiangolo.com/)
- [Flask documentation](https://flask.palletsprojects.com/)
- [pandas documentation](https://pandas.pydata.org/docs/)
- [GitHub Actions documentation](https://docs.github.com/en/actions)

## Contribution guidelines

Suggestions and corrections are welcome.

1. Open an issue describing the proposed change or missing topic.
2. Keep additions focused and link to authoritative resources.
3. Avoid duplicating topics already covered.
4. Use clear language and working links.
5. Submit a pull request with a concise explanation.

## License

This repository is distributed under the MIT License. See [LICENSE](LICENSE).
