# Scrum-Master Project Changes

This document outlines the changes required to the original open source scrum-master project before forking it internally.

## To-Do List

1. **Rework phase-planning into pr-planning**
   - Transform `.cursor/rules/phase-planning-guidance.mdc` into a PR-focused planning document
   - Minimally change the structure while updating the language used
   - Replace "phase" terminology with "PR" throughout the document
   - Maintain the core planning workflow but align it with PR-based development

2. **Remove the development doc**
   - Based on the notes, this document is considered "useless"
   - Need to locate and remove this file

3. **Terminology changes**
   - Update references from "phases" to "sprints" throughout the codebase
   - This will require modifying various files including rules and documentation
   - Ensure consistent terminology across all project files

4. **Add todo list rule**
   - Create a new rule for managing todo lists
   - Rule should only allow removing and appending items (no editing)
   - This will help maintain clean and consistent todo lists

5. **Create a high-level plan doc template**
   - Should be super short and easy to verify
   - Replace the current project planning approach
   - Focus on clarity and brevity

6. **Redefine sprint concept**
   - Change the sprint/phase concept to align with PR workflow
   - A sprint should be equivalent to a PR
   - This creates a more practical workflow tied to code changes

7. **Create retro document generator**
   - Implement functionality to automatically generate retrospective documents
   - Should produce useful summaries for PR documentation

8. **Check and update links**
   - Review the link to "Guide to engineering best practices with AI"
   - Determine if idea honing is better than requirements
   - Update any outdated or broken links

9. **Update cursor rules for project-specific directories**
   - Modify cursor rules to instruct the model not to use the generic "planning" directory
   - Instead, rules should direct the model to use a specific directory for each project it's tasked with maintaining
   - This will improve organization and prevent conflicts between different projects
   - Each project should have its own dedicated directory structure
