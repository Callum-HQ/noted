---
layout: page
icon: fas fa-code-fork
order: 3
---

Firstly, a big thank you for considering to contribute to this notes repository project.

This contribution guide (for the most part) assumes that you are an NP CSF student, and are familiar with `Git/GitHub`
and `Markdown`.

The ways to contribute to this project are:

1. Writing notes.
2. Improving/Fixing notes.
3. Adding new features.

The following sections will guide you on how to create new notes, format the notes, and contribute to the repository.

## Table of Contents:
- [Getting Started](#getting-started)
- [Creating a File](#creating-a-file)
- [Front Matter](#front-matter)
- [Formatting](#formatting)
- [Contributing to the repository](#contributing-to-the-repository)

## Getting Started

1. Fork the repository from GitHub.
2. Clone your forked repository to your local machine.
3. Install Ruby and Jekyll. Refer to the [Jekyll Docs](https://jekyllrb.com/docs/installation/) for installation
   instructions.
4. Install the dependencies by running `bundle install`.
5. Run the local server by running `bundle exec jekyll s`.

## Creating a File

- Notes are written in Markdown format, and follow the naming convention `YYYY-MM-DD-title.md`. `title` should be the
  content's (e.g. chapter) name.
- The file should be placed in the `_posts` directory.

## Front Matter

- The front matter of the file should contain the following:
  - `title`: The title of the note. Start with the module code in square brackets, followed by the title.
  - `author`: Your name. If this is your first time contributing, add your details in `_data/authors.yml`.
  - `categories`: The category of the note. This should be the module name in its full form.
- Additional fields can be added if necessary. Some examples include:
  - `authors: [author1, author2]`: A list of authors, if there are multiple authors.
  - `img_path: /img/path/`: Path to the image file's folder.
  - `math: true`: Enables LaTeX math rendering.
  - `mermaid: true`: Enables Mermaid diagram rendering. (Add ```mermaid``` tags to use Mermaid syntax)

## Formatting

- The notes should be formatted in Markdown. Refer to the [Markdown Guide](https://www.markdownguide.org/basic-syntax/)
  for more information.
- The notes should be well-structured, with headings, subheadings, and bullet points where necessary.
- There are additional formatting styles available with this website's theme (Referenced from [Chirpy's docs](https://chirpy.cotes.page/posts/text-and-typography/)):

Checkbox List:

- [ ] Task
  - [x] Step 1
  - [x] Step 2
  - [ ] Step 3

```
- [ ] Task
  - [x] Step 1
  - [x] Step 2
  - [ ] Step 3
```

Description List:

Name
: Some sort of definition, for instance.

```
Name
: Some sort of definition, for instance.
```

Block Quotes:

> This line shows the block quote.

```
> This line shows the block quote.
```

Prompts:

> An example showing the `tip` type prompt.
{: .prompt-tip }

> An example showing the `info` type prompt.
{: .prompt-info }

> An example showing the `warning` type prompt.
{: .prompt-warning }

> An example showing the `danger` type prompt.
{: .prompt-danger }


```
> An example showing the `tip` type prompt.
{: .prompt-tip }

> An example showing the `info` type prompt.
{: .prompt-info }

> An example showing the `warning` type prompt.
{: .prompt-warning }

> An example showing the `danger` type prompt.
{: .prompt-danger }
```

Tables
(Hint: Use a [Markdown Table Generator](https://www.tablesgenerator.com/markdown_tables) for this)

| Company                      | Contact          | Country |
|:-----------------------------|:-----------------|--------:|
| Alfreds Futterkiste          | Maria Anders     | Germany |
| Island Trading               | Helen Bennett    |      UK |
| Magazzini Alimentari Riuniti | Giovanni Rovelli |   Italy |

```
| Company                      | Contact          | Country |
| :--------------------------- | :--------------- | ------: |
| Alfreds Futterkiste          | Maria Anders     | Germany |
| Island Trading               | Helen Bennett    |      UK |
| Magazzini Alimentari Riuniti | Giovanni Rovelli |   Italy |
```

## Contributing to the repository

TODO
