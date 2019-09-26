# es-lint-cheat-sheet
A place to keep info related to es-lint that I Google for far too often

## How to turn off an ES lint rule
### For the next line:
```// eslint-disable-next-line <name of lint rule>```

### For a section of code: 
```
/*eslint-disable <(optional) name of lint rule> */

// Some non-lint conforming code

/*eslint-enable */
```
