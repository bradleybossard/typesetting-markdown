# typesetting-markdown


## Conversion
```
pandoc 01.md                   # Convert markdown to html
pandoc --to context 01.md      # Convert markdown to context
```

## Render
```
context --nonstopmode --batchmode 01.tex              # Generate .pdf and logs files
context --nonstopmode --batchmode --purgeall 01.tex   # Generate .pdf and delete ancillary files
```

### Links

[Dave Jarvis - Senior Software Developer](https://dave.autonoma.ca/blog/2019/05/22/typesetting-markdown-part-1/)

[Dave Jarvis - Senior Software Developer](https://dave.autonoma.ca/blog/2019/05/29/typesetting-markdown-part-2/)
