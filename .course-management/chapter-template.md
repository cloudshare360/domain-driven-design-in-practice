# Chapter Template Generator

## Reusable Template for New Chapters

Use this template structure for all future chapters:

### Folder Structure
```
[section]/[chapter-number-title]/
├── README.md                 # Chapter overview and navigation
├── transcript-full.md        # Complete formatted transcript
├── key-points.md            # Interview-ready bullet points
├── images/                  # Visual materials folder
├── metadata.json           # Chapter-specific metadata
└── content-processing-guide.md  # Processing instructions
```

### README.md Template
```markdown
# [Chapter Number] [Chapter Title]
*Duration: [Duration]*

## Overview
[Brief chapter description]

## Key Topics
[Topics covered - populate from transcript]

## Learning Objectives
By the end of this chapter, you will understand:
- [Objective 1]
- [Objective 2]

## Visual Resources
[Reference to images and diagrams]

## Content Structure
### 📝 Available Materials
- **README.md** - This overview and navigation
- **transcript-full.md** - Complete transcript content
- **key-points.md** - Bullet-point summary for interview prep
- **images/** - Visual diagrams and illustrations

## Navigation
- [Previous: [Previous Chapter]](../[previous-chapter]/README.md)
- [Next: [Next Chapter]](../[next-chapter]/README.md)
- [Back to Section [N]](../README.md)
- [Back to Course Overview](../../README.md)
```

### Processing Workflow
1. Create folder structure
2. Copy README template
3. Add content processing guide
4. Update metadata
5. Wait for user content (images + transcript)
6. Process transcript → bullet points
7. Organize images
8. Update navigation
9. Commit changes

This template ensures consistency across all chapters and sections.