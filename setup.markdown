---
date: 2019-06-06
tags: documentation
---

# Precis Setup

## Requirements

Precis has no dependencies other than *git* and these basic *nix commands:

- awk
- cat
- cut
- echo
- grep
- sed
- sh
- sort
- tr
- xargs

Most of these commands are installed by default. Otherwise, please install them using your operating system's package manager.

## Installation

- Fork or clone [this repo](https://github.com/abhin4v/precis) from Github.
- Delete all the markdown files:

```shell
$ rm *.md *.markdown tags/*.md
```

- Push to your own repo on Github.
- Enable Github pages for your repo in the repo settings with _master branch_ as the source.

## Usage

- Add a git pre commit hook with the following command:

```shell
bin/mk-site
```

- Modify `_config.yml` file with correct values as per your setup:

```yaml
# the name for your notes website
name: Precis

# the description of the notes website
description: Precis is a minimal note taking web-app built over Github Pages.
```

- Write notes in Markdown in the root directory of your repo. Upon committing the files in git, home page and tag pages will be auto-generated.
- Push to Github and wait for few minutes for the notes to be published.

## Notes Format

You can use [Github flavoured Markdown] to write your notes. You can add date and tags to the notes using the Markdown front-matter format.

A sample note:

```markdown
---
date: 2019-06-06
tags: meeting office
---

# Meetings Notes

- need to do things
- need to do more things
```

See [this demo note](./demo-note) to get a look and feel.

[Github flavoured Markdown]: https://guides.github.com/features/mastering-markdown/
