# Mirakl API Classification

This project uses a two-character prefix to identify the API family:

- **FR** - Front API  
- **OP** - Operator API  

This ensures developers always know which Bearer token applies to which endpoint.

## Folder Naming Convention
`<API Family>-<Capability Code>`

Examples:
- `FR-VL01` - Front API, Value Lists, Create
- `OP-HM02` - Operator API, Hierarchy Management, Update

## Authentication
Each API family uses its own Bearer token:
- `FR_BEARER_TOKEN`
- `OP_BEARER_TOKEN`

These are defined in the `mirakl-dev` environment.
