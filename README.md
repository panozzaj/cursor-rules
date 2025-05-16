# cursor-rules

Project `.cursor/rules` files, mostly ones that I have made.

These help the Cursor agent understand your project and preferences better. I recommend adding rules (or having Cursor add them!) when you run into something that you don't want it to run into again in the future.

## Main rules

These are in the `rules` directory. These rules should be general enough that they would be useful on a range of projects. I have been prefixing the rules with the language or framework they should be applied to.

## Local rules

While I recommend committing your `.cursor/rules` files to source control to make it easier for others to make progress, there may be some things that are specific to your local environment. For example, commands that only work on your computer due to having a custom command. Or just preferences that you don't think others would share. Or maybe something that you're not sure is baked enough to share with the whole team.

So you can add `.cursor/rules/local` to your `.gitignore` file. This will allow you to have a local rules directory that won't be shared with the rest of the team.

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
