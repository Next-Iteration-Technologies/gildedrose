# Copilot Instructions - Refactoring Project

This repository contains refactoring exercises. This file provides quick navigation to all AI agent guidance documents.

## Documentation Structure

### **Coding Standards & Guidelines**

#### [**Core Standards**](code-guidelines/core-standards.md)
**Purpose**: Universal coding principles applicable to all languages and projects  
**What it covers**:
- General principles (KISS, YAGNI, DRY, Boy Scout Rule)
- SOLID design principles
- Code smell detection and elimination
- Method/class size guidelines
- Naming conventions and readability requirements

**When to consider:** 
- Before writing any new code or refactoring
- When reviewing code quality
- Resolving design decisions (should I extract this method? is this class doing too much?)

## Recommended Workflow

1. **Before coding**: Reference [core-standards.md](code-guidelines/core-standards.md) for refactoring principles
2. **While refactoring**: Apply small, incremental changes following SOLID and code smell guidelines
3. **Always**: Run tests to verify behavior preservation

## Project-Specific Reminders

- This is a **refactoring workshop**, not feature development
- Preserve exact test outputs (string formatting matters!)
- Incremental changes > big rewrites

## Additional Resources

- Martin Fowler's "Refactoring: Improving the Design of Existing Code" (methodology basis)
- See [README.md](../README.md) for project overview and build instructions
