# Code style

Here you can find preferred code style configurations for various programming languages and programs, e.g. editors.

## Usage

### Installation
To install, run `npm i -D @philgibbins/code-style`.

**Note** this package includes the packages it configures, e.g. `sass-lint` and `tslint`, however it does not include
`typescript` itself.

### File organisation
If you're looking at the files in this repo:
- files in the root folder are for the mechanics/maintenance of this project only
- files in sub-folders are to be used by the projects that import this package
- if a file is needed for both of the above, the original file should be in a sub-folder, and the root directory should
  contain a symlink to that file. An example of this is the .editorconfig file.
