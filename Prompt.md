Create a PROJECT_CONTEXT.md file that serves as a complete handoff for a fresh Claude Code session.

Requirements:

- Keep it concise but complete. Do NOT summarize the conversation itself—summarize the PROJECT.
- Only include information that is still true. Ignore outdated discussions, failed ideas, and abandoned approaches.
- Remove duplicate information.
- Never include bugs, incorrect assumptions, speculative ideas, or temporary debugging attempts unless they are still unresolved and important.
- If there were multiple approaches discussed, only document the final chosen implementation.

Structure the document like this:

# Project Overview
- What this project is
- Main purpose
- Target users

# Tech Stack
- Frameworks
- Languages
- Libraries
- Database
- Deployment
- Authentication
- Other important tools

# Architecture
- High-level architecture
- Folder structure (only important folders)
- Main services and how they interact

# Features Implemented
List completed features with a short explanation.

# Current State
- What currently works
- What is partially finished
- Current branch or important status if applicable

# Important Decisions
Document architectural decisions and WHY they were made.

# Database
- Main tables
- Relationships
- Important constraints
- Security model (RLS, permissions, etc.)

# API
- Important endpoints
- External services
- Environment variables (names only, never values)

# Coding Conventions
- Existing patterns
- Naming conventions
- Components
- File organization
- Any project rules that should continue

# Known Issues
Only include issues that still exist and need to be fixed.

# Next Steps
Prioritized TODO list.

# Things NOT to Change
Anything intentionally designed that future sessions should preserve.

# Quick Start for Next Claude Session
In 10-20 bullet points, explain everything a fresh Claude should know before making changes.

Requirements:
- Do not invent information.
- Do not include unnecessary implementation details.
- Prefer bullet points over long paragraphs.
- Assume this file will be the ONLY context given to a brand new Claude session.
- Optimize for maximum usefulness with minimum length.
