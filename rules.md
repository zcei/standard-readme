# Rules

In the following a README is defined in its structure.


It consists of blocks, which is a (sub)section, often started by a heading.

A block can be nested into another block, and has one or more rules validating its integrity.

The position of a child block is defined by its parent.


## Blocks

### Heading
* requires a *title*
* (optional) Block: `Badges`
* followed by *description*

### Install(ation)
* Even if it's just `npm install <my-package>`, because sometimes it's not
* Sytem dependencies (like `ffmpeg`) are mentioned here

### Usage / Example
* A minimal example
* Should use / show most default values
* Shows how the developers intend the usage
* If CLI, use the most common flags in your call

### API
* [Discussion in #3](https://github.com/zcei/standard-readme/issues/3)

### License
* Is strictly mandatory (until further reviewed by lawyer/responsible persons - [Discussion](https://github.com/zcei/standard-readme/issues/4))
* (optional) link to `LICENSE` file (required, if `LICENSE` file is available in repo)


## Optional Blocks

### Badges
* http://shields.io/
* No constraints regarding flat, rounded, etc..
* Can also include images / gifs showing the projects' behavior

### Command Line

* Structure of `--help` output
* Can be more verbose

### Contributing

* See default text in `standard-readme`s readme
* (optional) Link to `CONTRIBUTING.md`
* Should be the very last block before `License`

### `Custom Block`

* Everything not defined in this standard will just be linted to ensure proper markdown formatting (thanks to awesome [`remark-lint`](https://github.com/wooorm/remark-lint/))
* Should come after required blocks, but before `License` block
