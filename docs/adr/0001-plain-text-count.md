# 0001 - The count is a plain text file

## Context

The auditors need to see every change: which line changed, who changed it, when, and why.

Git shows line changes, but only for text files. Excel is a binary file, so Git can only say that it changed, not what changed.

## Decision

The count is one plain text file, `count.txt`, with one product per line.

## Consequences

- Every change shows as a line in the history.
- Two people can change different lines at the same time.
- No formulas: a total has to be computed by hand or with a command.

