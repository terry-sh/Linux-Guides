# Search content

## Search for keyword

Type `/keyword` to search the matched content in the file forward, `%keyword` to search backward.

And `n` to search the next one, `N` to search the previous one.

## Search for matched parentheses

Place the cursor at `(`, `[` or `{`, and type `%`.

## Search and Replace

Type `:s/old/new/g` to replace the old with new.

- `:s/old/new` replace old with new
- `:s/old/new/g` replace old with new in a line
- `#,#s/old/new/g` replace between line (# is the line number)
- `:%s/old/new/g` replace all occurance in a file
- `:%s/old/new/gc` prompt before replace all occurance