### Duplicate or move lines

Given this text:

```
Shopping list
    Hardware store
        Buy nails
    Beauty parlor
        Buy nail polish remover
        Buy nails
```

Do the following exercises on the text above:

Start at 'H' on line 7
`:11copy.` - copies line to current line
`:11t.` - should do the same
`:t.` - duplicate current line
`:t$` - copy current line to end of file

`:11m$` - move line 11 to the end of the file
Visual select 2 lines
`:'<,'>m$` move the selected lines to the end of the file
        Buy nail polish remover
        Buy new hammer
        Buy nail polish remover
        Buy nail polish remover
