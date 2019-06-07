---
date: 2019-06-06
tags: documentation
---

# Precis Setup

## Requirements

You should have the following commands installed on the computer you want to take notes on:

- git
- sort
- tr
- sed
- xargs
- grep
- awk
- echo
- cat
- cut
- sh

Most of these commands are installed by default. Otherwise, please install them using your operating system's package manager.

## Installation

- Fork or clone [this repo](https://github.com/abhin4v/precis) from Github.
- Delete all the markdown files:
```shell
$ rm *.md *.markdown
```
- Push to your own repo on Github.
- Enable Github pages for your repo in the repo settings with _master branch_ as the source.

## Usage

- Add a git pre commit hook with the following command:
```
bin/mk-site
```
- Modify `_config.yml` file with correct values as per your setup.
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