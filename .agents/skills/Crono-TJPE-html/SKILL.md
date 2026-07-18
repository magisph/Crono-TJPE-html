```markdown
# Crono-TJPE-html Development Patterns

> Auto-generated skill from repository analysis

## Overview
This skill teaches the core development patterns and conventions used in the Crono-TJPE-html repository, a JavaScript codebase with no detected framework. You will learn how to structure files, write imports/exports, follow commit conventions, and understand the testing approach. This guide also provides suggested commands for common workflows.

## Coding Conventions

### File Naming
- Use **camelCase** for file names.
  - Example: `userProfile.js`, `dataFetcher.js`

### Import Style
- Use **relative imports** for modules.
  - Example:
    ```javascript
    import { fetchData } from './dataFetcher.js';
    ```

### Export Style
- Use **named exports**.
  - Example:
    ```javascript
    // In dataFetcher.js
    export function fetchData() { ... }
    ```

    ```javascript
    // In another file
    import { fetchData } from './dataFetcher.js';
    ```

### Commit Patterns
- Commit messages are **freeform** (no enforced prefixes).
- Average commit message length: **62 characters**.
  - Example:  
    ```
    Fix bug in date calculation for report generation
    ```

## Workflows

### Code Editing
**Trigger:** When adding or modifying features or bug fixes  
**Command:** `/edit-code`

1. Create or update JavaScript files using camelCase naming.
2. Use relative imports to include other modules.
3. Export functions or constants using named exports.
4. Write clear, descriptive commit messages.

### Testing
**Trigger:** When writing or updating tests  
**Command:** `/run-tests`

1. Create test files matching the pattern `*.test.*` (e.g., `userProfile.test.js`).
2. Write tests for your modules (testing framework is not specified).
3. Run tests using your preferred test runner.

## Testing Patterns

- Test files are named with the pattern: `*.test.*`  
  Example: `dataFetcher.test.js`
- The specific testing framework is **unknown**; use your preferred tool.
- Place tests alongside the code or in a `tests` directory as appropriate.

## Commands
| Command      | Purpose                                   |
|--------------|-------------------------------------------|
| /edit-code   | Start editing or adding JavaScript code   |
| /run-tests   | Run all test files matching `*.test.*`    |
```
