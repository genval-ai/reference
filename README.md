
# Getting Started with Genval

## Overview

Genval is a powerful tool that processes special GitHub Issue Templates. These templates allow users to provide input and include processing instructions for Genval to execute.

## Required Steps to Start

To get started with Genval, you need to copy two essential files into your repository.

### 1. GitHub Issue Templates Generation

To enable support for GitHub Issue Template generation:

1. Copy the following file:
   ```
   https://github.com/genval-ai/reference/blob/main/.genval/definitions/tasks/generate-issue-templates-from-task-definitions.md
   ```

2. Place it in your repo at:
   ```
   .genval/definitions/tasks/generate-issue-templates-from-task-definitions.md
   ```

### 2. Ad Hoc Refactoring

To enable support for ad hoc refactoring of your codebase:

1. Copy the following file:
   ```
   https://github.com/genval-ai/reference/blob/main/.genval/definitions/tasks/refactor.md
   ```

2. Place it in your repo at:
   ```
   .genval/definitions/tasks/refactor.md
   ```

## Generate Your First Issue Templates

After copying the two files mentioned above, follow these steps to generate your first issue templates:

1. Create a new issue in your repository.
2. Copy and paste the content of this file into the body of the issue:
   ```
   .genval/definitions/tasks/generate-issue-templates-from-task-definitions.md
   ```
3. Create the issue.
4. Genval will start working on the issue, generating GitHub issue templates as requested.
5. Once the task is complete, merge the feature branch back into your main (or default) branch to use the new issue templates.

By following these steps, you'll have Genval up and running in your repository, ready to streamline your workflow with custom issue templates and ad hoc refactoring capabilities.
