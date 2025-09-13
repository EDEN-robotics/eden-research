# Contributing to Eden Research

Thank you for contributing to the Eden Research Repository! This document provides guidelines for adding research resources and maintaining the knowledge base.

## 📋 General Guidelines

### Before Adding Content
- **Check existing resources**: Search the repository to avoid duplicates
- **Choose the right location**: Place content in the most relevant subsystem folder
- **Follow naming conventions**: Use clear, descriptive filenames
- **Keep it organized**: Maintain the structure and purpose of each folder

### Quality Standards
- **Be concise but informative**: Provide enough detail to be useful
- **Include context**: Explain why a resource is relevant to Eden
- **Keep it current**: Update or remove outdated information
- **Use proper formatting**: Follow markdown best practices

## 📁 Folder-Specific Guidelines

### Reading Lists (`reading-list.md`)

**Purpose**: Curated collection of external resources

**Format**:
```markdown
## [Category Name]
- **[Resource Title](URL)** - Brief description of relevance to Eden
- **[Another Resource](URL)** - Description
```

**Guidelines**:
- Organize by category (Papers, Documentation, Videos, Tools, etc.)
- Include brief descriptions explaining relevance
- Use consistent formatting
- Add dates when resources are added
- Remove or mark outdated resources

**Example**:
```markdown
## Papers & Publications
- **"Robust Robot Learning" (2023)** - https://example.com/paper - Novel approach to robot learning that could improve Eden's adaptability
- **"Multi-Agent Systems in Robotics" (2022)** - https://example.com/paper2 - Relevant for Eden's distributed architecture
```

### Notes (`notes/`)

**Purpose**: Freeform research notes, meeting summaries, and personal insights

**Naming Convention**: `YYYY-MM-DD-descriptive-title.md`

**Format**:
```markdown
# [Title]

**Date**: YYYY-MM-DD  
**Author**: [Name]  
**Context**: [Meeting/Research/Experiment]

## Key Points
- Point 1
- Point 2

## Action Items
- [ ] Task 1
- [ ] Task 2

## Resources
- [Link 1](URL)
- [Link 2](URL)
```

**Guidelines**:
- Include date and context
- Use clear headings and bullet points
- Include action items when relevant
- Link to related resources
- Be informal but organized

### Outlines (`outlines/`)

**Purpose**: Structured research plans, technical specifications, and project roadmaps

**Naming Convention**: `descriptive-title.md`

**Format**:
```markdown
# [Title]

**Status**: [Draft/In Progress/Complete]  
**Last Updated**: YYYY-MM-DD  
**Author**: [Name]

## Overview
Brief description of the research area or project.

## Objectives
- Objective 1
- Objective 2

## Research Questions
1. Question 1
2. Question 2

## Methodology
Description of approach and methods.

## Timeline
- Phase 1: [Description] - [Timeline]
- Phase 2: [Description] - [Timeline]

## Resources
- [Resource 1](URL)
- [Resource 2](URL)

## Next Steps
- [ ] Action 1
- [ ] Action 2
```

**Guidelines**:
- Use clear, structured format
- Include status and timeline information
- Focus on actionable insights
- Link to relevant resources
- Update regularly as research progresses

## 🔧 Technical Guidelines

### Markdown Formatting
- Use proper heading hierarchy (`#`, `##`, `###`)
- Use bullet points for lists
- Include links with descriptive text
- Use code blocks for technical content
- Add horizontal rules (`---`) to separate sections

### File Naming
- Use lowercase with hyphens: `robot-learning-notes.md`
- Include dates when relevant: `2024-01-15-meeting-notes.md`
- Be descriptive but concise
- Avoid special characters and spaces

### Links and References
- Use full URLs for external links
- Use relative paths for internal links
- Include link descriptions
- Verify links are working

## 🚫 What Not to Include

- **Personal information**: No private data or sensitive information
- **Large files**: Use links to external storage for large documents
- **Duplicate content**: Check existing resources first
- **Unformatted content**: Follow markdown standards
- **Outdated information**: Update or remove old content

## 🔄 Review Process

### Before Submitting
1. **Self-review**: Check formatting, links, and content quality
2. **Search for duplicates**: Ensure content isn't already present
3. **Verify links**: Make sure all links work
4. **Follow guidelines**: Ensure content follows this document

### After Adding Content
1. **Update relevant reading lists**: If you added a new resource
2. **Cross-reference**: Link to related content in other folders
3. **Notify team**: Share relevant additions with team members
4. **Follow up**: Update content as research progresses

## 📞 Getting Help

- **Questions about content**: Ask in team channels
- **Technical issues**: Check existing documentation first
- **Suggestions**: Open an issue or discuss with team leads
- **Major changes**: Discuss with team before implementing

## 🎯 Best Practices

1. **Regular updates**: Keep content current and relevant
2. **Cross-pollination**: Share insights across subsystem boundaries
3. **Documentation**: Explain your reasoning and context
4. **Collaboration**: Build on others' work and give credit
5. **Quality over quantity**: Focus on useful, well-organized content

---

*Remember: This repository is a shared resource. Your contributions help the entire Eden team. Take pride in creating content that others will find valuable!*
