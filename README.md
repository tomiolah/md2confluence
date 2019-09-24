# md2confluence
A simple NodeJS program, that converts Markdown files to Atlassian Confluence syntax

## Running

`$ node md2conf.js <input_markdown_file> [-o <output_file>]`

## Features implemented
[Confluence syntax docs](https://confluence.atlassian.com/doc/confluence-wiki-markup-251003035.html)

[Markdown Cheatsheet used](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

- inline monospace ✅
- headings ✅
- code block ✅
- bold ✅
- italic ✅
- hyperlinks ✅
- lists (with tabs) ✅
  - unordered ✅
  - ordered / numbered ✅
- images
- deleted (~xyz~ => --xyz--)
- tables