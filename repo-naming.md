# Repository Naming Guidelines

## Format
- Use **lowercase kebab-case**
- Example: mountain-peak or pacific-coastal-mountains

### Rationale
- Most common in modern repos
- Matches URLs cleanly
- Works well with CLI + scripts
- Avoids case-sensitivity issues

## Naming by Type

### Products
- Use simple names
- Example: mountain

#### Good suffix patterns for Products
- `-api` for a product's application programming interface
- `-worker` for product application's processors/threads
- `-database` for the database component of a product
- `-docs` for documentation specific to the product

#### Examples:
- mountain-pass-api
- mountain-pass-worker
- mountain-pass-database
- mountain-pass-docs

### Projects
- Prefix with `proj-`
- Example: proj-asip

### Documentation-only
- Prefix with `docs-`
- Example: docs-data-governance

### Experiments
- Prefix with `poc-`
- Example: poc-identity-matching

### Infrastructure
- Prefix with `infra-`
- Example: infra-docker-base

## Notes
- Avoid underscores
- Avoid inconsistent casing
- Prefer clarity over brevity
- Generally prefer full words over abbreviations, such as `database` over `db` (but not always as, for example,  `api` is preferred over `application-programming-interface`)

### See:
- [New Repository Checklist](./new-repo-checklist.md)