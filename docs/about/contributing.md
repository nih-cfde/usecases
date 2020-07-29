---
layout: default
title: Contributing
parent: Home
nav_order: 2
---

# Contributing to the nih-cfde Use Case Repository

Hello, and thank you for your interest in contributing to the CFDE Use Case Repository!

By contributing to this repository, you agree:

1.  To obey the [Code of Conduct](./CODEOFCONDUCT.md)
2.  To release all your contributions under the same terms as the license itself: the [Creative Commons Zero](./LICENSE.md) (aka Public Domain) license

If you are OK with these two conditions, then we welcome both you and your contribution!

## How to add content

If you have a suggestion for a new use case concept and are not familiar with GitHub, you can [email your idea to us](mailto:autohelp+int+851+6545985337373134556@CFDE.groups.io).

If you are familiar with GitHub please either:

  - [open an issue](https://github.com/nih-cfde/usecases/issues/new) describing your idea
  
  - or write up your use case and submit it as a pull request (PR). Please follow the [Use Case Style Guide](#usecasestyle) below.

### PR format
If you are submitting a pull request, please create one pull request per use case so admin can check the complete change. See [template]().

PR process:

1. Preview new changes
- Create a new branch in the [use cases repo](https://github.com/nih-cfde/usecases)
- Use the [use case file templates](../template_files) to add your new use case files
- Submit a PR from your branch to the `preview` branch. After you submit the PR, make sure the repo checks complete (green check mark).
- If the checks complete successfully, merge the changes and view the [preview website](https://cfde-usecases.readthedocs-hosted.com/en/preview/) to check the changes. It can take ~30 minutes for the new changes to appear. If the checks failed, you can submit an issue for help.

2. If you are satisfied with the changes, submit a new PR from your branch to the `master` branch.
- See [template]()
- Request review from @Acharbonneau and @marisalim
- Please allow up to one week for admin to review your request


### Use Case approval process
- The Use Case committee will mark proposed use cases, and corresponding requirements pages, as `in progress`, `approved`, and `done`, as appropriate:

Progress | Symbol
--- | ---
in progress | &#x23F3;
approved | &#x1F44C;
done | &#x2705;

If you have any questions about contributing, please [open an issue](https://github.com/nih-cfde/usecases/issues/new) and we will lend a hand ASAP.

Thank you for being here and for being a part of the CFDE project!

## Use Case Repository Style Guide <a name="usecasestyle"></a>

### Use Case Structure
- All Use Cases must have:
    - a **Persona**
    - an **Objective**
    - a **Summary** of the Objective
    - specific **User Tasks**
    - technical infrastructure **Requirements** for each User Task
- See [glossary](./glossary.md) for definitions
- Each persona, objective, user task, and requirement needs its own description page that will be linked to the corresponding use case page(s). Common user tasks and requirements should be reused across use cases.

### General File Format

**File format** for all files should be written in Markdown.

- For help with Markdown syntax, see this [basic syntax guide](https://www.markdownguide.org/basic-syntax/)
- To add links to other pages:
    
```
# syntax
[<text to click on>](<Github repo relative path to file>)

# This is an example for a link to the Personas description page for 'Clinical Researcher':
[Clinical Researcher](../personas/clinical-researcher.md)
```
    
The **Site index** is automatically created by yaml headers in each file (only the title will be visible on the rendered website). See [template files](../template_files) for example structure.

  The `parent` yaml value depends on the website tab the Use Case file appears in:
  
  `parent:` value | Type
  --- | ---
  `Use Cases` | for the main Use Case file
  `Personas` | for persona files
  `Objectives` | for objective files
  `User Tasks` | for user task files
  `Requirements` | for requirements files
  
  The Use Case committee will finalize yaml header page numbers to ensure they do not clash with existing files.
  
**File names** should be lower case, have hyphens, and match the heading. Use Case (`ucXXXX`), User Task (`tXXXX`), and Requirement (`rXXXXX`) files should include a file ID numbered in order of appearance in this Use Case Repository website.

   File type | Example
   --- | ---
   use case | uc0001-researcher-browse-and-filter.md
   persona | clinical-researcher.md
   objective | create-data-release.md
   user task | t0001-access-cfde-interface.md
   requirement | r00001-the-interface-will-support-gui-web-access-to-end-users.md
   
   The Use Case committee will finalize Use Case, User Task, and Requirement file IDs to ensure they do not clash with existing IDs.

### `Use Case` files
- Use Case titles always begin with their `UCXXXX` ID
- Required sections:
    - yaml index header
    - Page header: title, date completed (`<month> <year>`), persona, objective
    - `Summary`: a short summary of the use case
    - `User Tasks`: a bullet point list of the tasks required for the use case, including links to each task page. Tasks are numbered by `TXXXX`.
    - `Requirements`: a bullet point list of the requirements for each task, including links to each requirement page. Requirements are numbered by `RXXXXX`.
- The persona, objective, user tasks, and requirements need to be linked to their corresponding description page (detailed in the following sections)
- See [use case file template](../template_files/use-case-template.md)
- Use case files should be saved [here](../use-cases/)

### `Persona` files
- Required sections:
    - yaml index header
    - Short description of their biological/computational experience, their role and responsibilities, and relation to any of the other Personas in the Use Cases Repository
    - A section listing assumptions about the persona's credentials e.g., access to the CFDE
- See [persona file template](../template_files/persona-template.md)
- Persona files should be saved [here](../personas/)

### `Objective` files
- Required sections:
    - yaml index header
    - `<name of the task>:`: brief ~1 sentence description of the task
- See [objective file template](../template_files/objective-template.md)
- Objective files should be saved [here](../objectives/)

### `User task` files
- The User Tasks title should be short and self-explanatory, but please add a short description as needed for clarity
- User Task titles always begin with their `TXXXX` ID
- Required sections:
    - yaml index header
    - `Appears in Use Cases:`: bullet point list of the use case(s) that the task appears in, with page link to the use case page(s)
- See [user task file template](../template_files/user-task-template.md)
- User task files should be saved [here](../user-tasks/)

### `Requirement` files
- The Requirements title should be short and self-explanatory, but please add a short description as needed for clarity
- Requirement titles always begin with their `RXXXXX` ID
- Required sections:
    - yaml index header
    - Requirement title (same as yaml index title)
    - An `Appears in` section with two sub-sections:
      - Under `User Tasks`: bullet point list of the task(s) that the requirement appears in, with page link to the user task page
      - Under `Use Cases`: bullet point list of the use case(s) that the requirement appears in, with page link to the use case page(s)
- See [requirement file template](../template_files/requirement-template.md)
- Requirements files should be saved [here](../requirements/)
