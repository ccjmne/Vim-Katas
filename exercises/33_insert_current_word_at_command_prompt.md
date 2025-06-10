### Insert current word at the command prompt

Rename the variable 'counter' to 'counter':

```javascript
var counter;
for (counter=1; counter <= 10; counter++) {
  // Do something with counter
};
```

Start on line 6 at the 't' character
`*` - selects all the words 'counter'
`cwcounter<Esc>` - replaces the word with counter
`:%s//<C-r><C-w>/g` - gets the current word for the substitute command
