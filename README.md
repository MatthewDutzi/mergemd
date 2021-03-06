
## Installation

### Install from npm/yarn

```bash
$ npm install -g @matthewdutzi/mergemd
```

or

```bash
$ yarn global add @matthewdutzi/mergemd
```

to install globally.

### Clone to local

Clone this repo, `cd` into it, and then run

```bash
$ npm link
```

## Usage

This package will merge all the files in a directory into one file called `merged.md` or `merged.mdx`.

It now works for markdown files, but should really work for plain text and code files.

### Provide directory

```bash
$ merge path/to/directory
```

This merges all the files in `path/to/directory`.

Don't know what directory you want? Try running `$ pwd` inside the folder you want.

### No provided directory

```bash
$ merge
```

This merges all the files in the directory where this command is run.

### Options

```bash
$ merge -mdx
```
This changes output file extension from '.md' to '.mdx'

```bash
$ merge -no-file-info
```
This disables file info comments of merged files in output file
## License

Copyright 2017 Mandy Chen

Licensed under [MIT](./license)
