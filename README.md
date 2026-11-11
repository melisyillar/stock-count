# stock-count

The stock count of Selin's warehouse: every product, with its number.

## The count

- The count lives in `count.txt`.
- One product per line: a name, one space, a number.
- New products go at the end of the file.

## How to change it

1. Open an issue.
2. Make a branch.
3. Commit, push, and open a pull request.
4. Somebody else reviews it before it is merged.

## Who does what

| Who | What |
|---|---|
| Selin | owns the count, merges pull requests |
| Kaan | counts, reviews pull requests |

## Read the history

Every line of the count has a commit behind it:

```bash
git log --oneline count.txt
git blame count.txt
```
