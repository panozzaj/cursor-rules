# cursor-rules

Project `.cursor/rules` files, mostly ones that I have made.

## Helpful tooling

If there are a bunch of directories at the same level as this directory, you
can use the following command to find your own `.cursor/rules` files:

```
find .. -maxdepth 4 -path '*/.cursor/rules' -print
```

## Helpful documentation

Right now the structure of rules and the frontmatter is not super-well documented.

 - [Cursor documentation](https://docs.cursor.com/context/rules-for-ai)
 - [Cursor changelog](https://www.cursor.com/changelog)
   - Since 0.47.x: "Rules: Allow nested .cursor/rules directories..."
 - Useful posts from Geoffrey Huntley
   - https://ghuntley.com/stdlib
   - https://ghuntley.com/specs
 - [Interesting way of testing rules](https://github.com/codekiln/cursor-project-rule-test)
