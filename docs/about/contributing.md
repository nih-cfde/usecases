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
  
  - or write up your use case and submit it as a pull request (PR) at [https://github.com/nih-cfde/usecases](https://github.com/nih-cfde/usecases). Please follow the [Use Case Style Guide](#usecasestyle) below.

### PR format
If you are submitting a pull request:

- Please create one pull request per use case so admin can check the complete change

- Request review from @Acharbonneau and @marisalim

- Please allow up to one week for admin to review your request

### Use Case approval process
- The Use Case committee will mark proposed use cases as `in progress`, `approved`, and `done`, as appropriate.
  
- If the Use Case has been approved, a &#x2705; will be added next to the Use Case tab title, as well as its corresponding Requirements tab titles.

If you have any questions about contributing, please [open an issue](https://github.com/nih-cfde/usecases/issues/new) and we will lend a hand ASAP.

Thank you for being here and for being a part of the CFDE project.

## Use Case Repository Style Guide <a name="usecasestyle"></a>

### Use Case Structure
- All Use Cases must have:
    - a **Persona**
    - an **Objective**
    - a **Summary** of the Objective
    - specific **User Tasks**
    - technical infrastructure **Requirements** for each User Task
- See [glossary](./glossary.md) for definitions
- Each persona, objective, user task, and requirement needs its own description page that will be linked to in the corresponding use case page(s) (some common user tasks and requirements may be repeated across use cases).

### General File Format

- **File format**: all files should be written in Markdown

    - For help with Markdown syntax, see this [basic syntax guide](https://www.markdownguide.org/basic-syntax/)
  
    - To add links to other pages:
  
    ```
    [<text to click on>](<link to file>)
    ```
    
    This is an example for a link to the Personas description page for 'Clinical Researcher':
    
    ```
    [Clinical Researcher](../personas/clinical-researcher.md)
    ```
    
- **Site index**: automatically created by yaml headers in each file (only the title is visible on the rendered website). The yaml header must be formatted as follows:

  ```
  
  ---
  
  layout: default
  
  title: "<Use case title>"
  
  nav_order: <page number>
  
  parent: <website tab name>
  
  completed: <month year>
  
  has_children: false
  
  ---
  
  ```
  
  This is an example for the 'UC0001' Use Case:
  
  ```
  
  ---
  
  layout: default
  
  title: "UC0001 Researcher Browse and Filter"
  
  nav_order: 1
  
  parent: Use Cases
  
  completed: June 2020
  
  has_children: false
  
  ---
  
  ```
  
  The `parent` value depends on the Use Case file type:
  
  `parent:` value | Type
  --- | ---
  `Use Cases` | for the main Use Case file
  `Personas` | for persona files
  `Objectives` | for objective files
  `User Tasks` | for user task files
  `Requirements` | for requirements files
  
- **File names**: should be lower case, have hyphens, and match the heading. Use Case (`ucXXXX`), User Task (`tXXXX`), and Requirement (`rXXXXX`) files should include a file code numbered in order of appearance in this Use Case Library website.

   File type | Example
   --- | ---
   use case | uc0001-researcher-browse-and-filter.md
   persona | clinical-researcher.md
   objective | create-data-release.md
   user task | t0001-access-cfde-interface.md
   requirement | r00001-the-interface-will-support-gui-web-access-to-end-users.md

#### `Use Case` files
- Required sections:
    - yaml index header
    - Page header: title, date completed (`<month> <year>`), persona, objective
    
    ```
    
    <Title>
    
    Completed:
    
    Persona:
    
    Objective:
    
    ```
    
    - `Summary`: a short summary of the use case
    - `User Tasks`: a bullet point list of the tasks required for the use case, including links to each task page. Tasks are numbered by `TXXXX`.
    - `Requirements`: a bullet point list of the requirements for each task, including links to each requirement page. Requirements are numbered by `RXXXXX`.
- The persona, objective, user tasks, and requirements need to be linked to their corresponding description page (detailed in the following sections)

#### `Persona` files
- Required sections:
    - yaml index header
    - Short description of their biological/computational experience and relation to any of the other Personas in the Use Cases Repository
    - Persona title (same as yaml index title)
    - Short description of the type of work they do, slightly more detailed than the first description
    - A section listing assumptions about the persona's credentials e.g., access to the CFDE, formatted as follows:
    
    ```
    
    Assumptions
    
          Users with this persona:
          
    ```

#### `Objective` files
- Required sections:
    - yaml index header
    - `<name of the task>:`: brief ~1 sentence description of the task

#### `User task` files
- Required sections:
    - yaml index header
    - `Appears in Use Cases:`: bullet point list of the use case(s) that the task appears in, with page link to the use case page(s)

#### `Requirement` files
- Required sections:
    - yaml index header
    - Requirement title (same as yaml index title)
    - An `Appears in` section with two sub-sections:
  
    ```
    
    Appears in:
    
        User Tasks

        Use Cases
        
    ```
  
      - Under `User Tasks`: bullet point list of the task(s) that the requirement appears in, with page link to the user task page
      - Under `Use Cases`: bullet point list of the use case(s) that the requirement appears in, with page link to the use case page(s)

