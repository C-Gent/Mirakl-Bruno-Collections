# Collections API Structure

This directory contains all Mirakl API endpoints grouped by API family and capability code.

## API Families
- **FR** - Front API (uses Front Bearer Token)
- **OP** - Operator API (uses Operator Bearer Token)

## Capability Codes
Each subfolder represents a specific capability:
- **VL** - Value Lists
- **HM** - Hierarchy Management
- **PM** - Product Management
- **VM** - Value List Management (Operator)

## Structure
Each capability folder will contain:
- `request.json` - Bruno request definition
- `script.js` - modular JS logic
- `test.json` - Bruno test definition

This structure ensures modularity, clarity, and consistent authentication handling.
