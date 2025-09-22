# MWRA Glossary Project - AI Coding Agent Instructions

## Project Overview
This is the Massachusetts Water Resources Authority (MWRA) glossary project - a documentation repository for water utility terminology and definitions. The project is currently in its initial phase with minimal structure.

## Repository Structure
```
mwra-glossary./
├── README.md          # Project overview (currently minimal)
├── LICENSE            # Apache 2.0 license
└── .github/          # GitHub configuration and workflows
    └── copilot-instructions.md
```

## Project Purpose & Context
- **Domain**: Water utility terminology and regulatory compliance
- **Audience**: MWRA staff, water utility professionals, regulatory bodies
- **Content Type**: Technical definitions, procedures, compliance documentation
- **License**: Apache 2.0 (open source, attribution required)

## Key Development Patterns

### File Organization
- Use clear, hierarchical naming for glossary entries
- Consider organizing by topic areas (e.g., `treatment/`, `distribution/`, `compliance/`)
- Maintain consistent markdown formatting for definitions
- Include cross-references between related terms

### Documentation Standards
- Write definitions in plain language while maintaining technical accuracy
- Include relevant regulatory references (EPA, DEP, etc.)
- Use consistent terminology throughout all entries
- Provide examples or context where helpful for complex terms

### Content Guidelines
- **Accuracy**: All technical information must be current and verified
- **Accessibility**: Definitions should be understandable to various skill levels
- **Completeness**: Include common abbreviations, acronyms, and alternative terms
- **Attribution**: Cite sources for regulatory or technical definitions

## Recommended Development Workflow

1. **Research Phase**: Verify terminology with MWRA subject matter experts
2. **Draft**: Create markdown files with clear structure
3. **Review**: Ensure technical accuracy and regulatory compliance
4. **Cross-reference**: Link related terms and concepts
5. **Validate**: Check for consistency with existing entries

## File Naming Conventions
- Use lowercase with hyphens for file names: `chlorine-residual.md`
- Group related terms in subdirectories: `treatment/coagulation.md`
- Use descriptive names that match the primary term being defined

## Future Architecture Considerations
As the project grows, consider:
- Search functionality implementation
- Term categorization system
- Regulatory compliance tracking
- Version control for definition updates
- Integration with MWRA's existing documentation systems

## Contributing Guidelines
- Maintain the Apache 2.0 license requirements
- Follow existing formatting patterns
- Ensure all content is appropriate for public consumption
- Verify technical accuracy before submission