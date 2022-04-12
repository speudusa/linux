---
title: "STDOUT: Redirect Append"
date: 2022-04-08T13:54:05-05:00
draft: false
weight: 105
originalAuthor: <no value> # to be set by page creator
originalAuthorGitHub: <no value> # to be set by page creator
reviewer: # to be set by the page reviewer
reviewerGitHub: # to be set by the page reviewer
lastEditor: # update any time edits are made after review
lastEditorGitHub: # update any time edits are made after review
lastMod: # UPDATE ANY TIME CHANGES ARE MADE
---

## Bash Output

- STDOUT
  - When working within a bash terminal it will regularly output information or text in response to a command entered as `stdin`.
  - Bash can take the output and write the information to a file in two ways:
    - Overwrite target file with output using the `>` operator learned in previous lesson
    - Append output to file with the `>>` operator

## Examples

- `ls -a >> ls-a-example`
- `history > history.txt`
  - `history >> history.txt`