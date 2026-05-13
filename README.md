# Open Source Skills

A collection of open-source [Factory](https://factory.ai) skills and droids for use with Droid. Distributed as a Factory plugin.

## Skills

### COBOL to Java Conversion

Convert COBOL mainframe applications to modern Java following mainframe modernization best practices. Covers CICS transactions, batch programs, VSAM files, DB2 integration, and data structure migrations.

**Includes:**

- **Checklists** -- Pre-conversion, post-conversion validation, and data migration
- **Examples** -- Batch, CICS, and copybook conversion walkthroughs
- **Mappings** -- CICS-to-Spring, COBOL-to-Java data types, VSAM-to-SQL
- **References** -- AWS Transform guide and common pitfalls
- **Scripts** -- COBOL analysis and test data generation
- **Templates** -- Controller, service, and repository Java templates

## Droids

### COBOL Analyzer

Analyzes COBOL mainframe applications for modernization. Performs static analysis of programs, copybooks, CICS transactions, VSAM operations, and embedded SQL. Extracts dependencies, business rules, and quality metrics. Identifies modernization blockers and generates migration roadmaps.

**Capabilities:**

- **Program Metrics** -- Cyclomatic complexity, dead code detection, maintainability scoring
- **Dependency Mapping** -- Copybooks, CALL targets, file references, CICS transaction relationships
- **CICS Command Analysis** -- Terminal I/O, file I/O, program control, resource control
- **VSAM File Operations** -- Dataset organization, key structures, access patterns
- **DB2/SQL Analysis** -- Embedded SQL, cursors, host variables, dynamic SQL
- **Data Structure Analysis** -- REDEFINES, OCCURS, COMP-3, nested structures
- **Business Rule Extraction** -- Conditional logic, computational rules, validation rules
- **Modernization Blockers** -- GOTO/ALTER, PERFORM THRU, inline SORT/MERGE

## Installation

### As a plugin (recommended)

Add this repo as a marketplace, then install the plugin:

```bash
droid plugin marketplace add https://github.com/factory-sam/open-source-skills
droid plugin install mainframe-modernization@open-source-skills
```

Or use the interactive plugin manager:

```
/plugins
```

### Manual

Clone this repo and copy the contents of `mainframe-modernization/skills/` and `mainframe-modernization/droids/` into your project's `.factory/` directory.

## License

MIT
