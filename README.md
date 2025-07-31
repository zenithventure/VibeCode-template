# VibeCode Template

A template project to help developers quickly start their hackathon projects using Vibe Coding AI assistance.

## What is this?

This template provides a structured approach to building applications using AI-powered development. It includes pre-written prompts and a systematic workflow to take your project from initial idea to full implementation.

## Getting Started

1. **Clone this template** to your local machine
2. **Add your preliminary information** in the `0-Prelim/` folder (meeting notes, project briefs, etc.)
3. **Use the prompts** in `prompt.md` to generate your project step-by-step

## Workflow

The template follows a 4-phase development process:

### Phase 1: System Requirements
Use the business requirements prompt to generate:
- System overview
- Core requirements  
- Technical requirements
- Performance requirements
- Constraints
- Success criteria

### Phase 2: Technical Documentation
Generate detailed technical specifications:
- System architecture diagrams
- Screen breakdown
- API specifications
- Database design
- Sequence diagrams

### Phase 3: Design Documentation
Create visual and UX guidelines:
- Design guidelines
- Color palette
- Screen wireframes

### Phase 4: Implementation
Choose your implementation stack:
- **Next.js Web App** - Modern React web application
- **React Native Mobile** - Cross-platform mobile app
- **Full-Stack** - Next.js + Express + PostgreSQL

## Key Features

- **Structured naming convention** - Numeric prefixes ensure proper folder ordering
- **Multiple implementation options** - Web, mobile, or full-stack
- **Built-in authentication** - Google/Microsoft SSO + demo login
- **TypeScript support** - Type safety throughout the stack
- **Responsive design** - Mobile and desktop ready

## Folder Structure

```
VibeCode-template/
├── 0-Prelim/           # Your initial project information
├── prompt.md           # AI prompts for each development phase
└── README.md           # This file
```

After running the prompts, your project will expand to:

```
your-project/
├── 0-Prelim/
├── 1-SystemRequirements/
├── 2-TechnicalDocuments/
├── 3-DesignDocuments/
└── 4-Implementation/
```

## Usage

1. Place your project brief, meeting notes, or requirements in `0-Prelim/`
2. Copy prompts from `prompt.md` into your Vibe Coding interface
3. Follow the prompts sequentially (1 → 2 → 3 → 4)
4. Customize the generated content as needed

## Tips

- Keep the numeric folder naming convention for proper ordering
- Start with thorough requirements - they drive everything else
- Choose your implementation stack based on your target audience
- The example Greenhouse Management System shows the complete workflow

## Support

For issues or questions about this template, refer to the Vibe Coding documentation or community resources.